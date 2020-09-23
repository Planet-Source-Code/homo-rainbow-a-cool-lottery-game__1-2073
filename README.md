<div align="center">

## A Cool Lottery Game


</div>

### Description

A cool wat to play the lottery.
 
### More Info
 
'first you need to make a text box then copy it 5 times.this makes 6 text boxs.

'second you need make a label, rename it lblLottery then copy it 5 times. this makes 6

'make 2 command buttons, make command2's caption "Submit The Numbers"

'make command1's caption "Play Again"


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[homo rainbow](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/homo-rainbow.md)
**Level**          |Unknown
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/homo-rainbow-a-cool-lottery-game__1-2073/archive/master.zip)





### Source Code

```
dim T as integer
dim random as integer
dim I as integer
Private Sub command2_Click()
 For I = 0 To 5
  Randomize
  Random = Int((Rnd * 51) + 1)
  lblLottery(I).Caption = Random
 Next I
End Sub
Private Sub Command1_Click()
Text1(0).SetFocus
For T = 0 To 5
Text1(T) = ""
Next T
For I = 0 To 5
lblLottery(I).Caption = ""
Next I
End Sub
```

