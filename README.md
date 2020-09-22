<div align="center">

## count down to zero with a given number


</div>

### Description

this is very simple and is for begginners... it askes you to input a number... it will then loop messege box's until the number is counted down to zero.... then it replies with another messege box that says... "thats all"...... (updated code#2)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Branden](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/branden.md)
**Level**          |Beginner
**User Rating**    |3.0 (9 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[String Manipulation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/string-manipulation__1-5.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/branden-count-down-to-zero-with-a-given-number__1-8459/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
Dim x As String
x = InputBox("enter a number u would like To count down from")
Do While x > 0
x = x - 1
If x = 0 Then
MsgBox "Thats all"
Else
MsgBox x
End If
Loop
End Sub
```

