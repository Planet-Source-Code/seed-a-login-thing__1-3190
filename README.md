<div align="center">

## A login thing


</div>

### Description

This is a ordinary login program, kind of like aol. It makes sure the person enters a username and a password more than 1 letter. It's pretty cool, I think. I would use something like this on all my projects.
 
### More Info
 
1. 2 forms

2. on form 1, put 2 textboxes and a commandbutton

3. thats all

4. use the below code in form1s general decs...


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeeD](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seed.md)
**Level**          |Unknown
**User Rating**    |3.4 (34 globes from 10 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seed-a-login-thing__1-3190/archive/master.zip)





### Source Code

```
Form_Load()
  Me.Caption = "Login for project"
  Text1.Text = "username"
  Text2.Text = "password"
  Command1.Caption = "Next" '<or "ok" or something
End Sub
'the next code is for command1
Private Sub Command1_Click()
  If Text1.Text <> "" And Text2.Text > "*" Then
  Form2.Show
  Else MsgBox "An error was detected, password must be at least 2 digits and a username must be entered.", 8, "Invalid entry"
  End If
  End Sub
```

