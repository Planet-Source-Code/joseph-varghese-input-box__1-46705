<div align="center">

## Input box


</div>

### Description

Hello friends i dont know how many people know this but not all,,this tutorial will let you know how to handle cancel button on input box

most of them dose this by checking the length of the value returned by the input box even though it works it is not the proper way todo it check ot this material Have fun...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Joseph Varghese](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/joseph-varghese.md)
**Level**          |Intermediate
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/joseph-varghese-input-box__1-46705/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
Dim str1 as String
str1=Inputbox("Enter some thing")
If Strptr(str1)<>0 then
'code for click of ok button
Msgbox "OK CLICKED"
Elseif Strptr(str1)=0 then
'code for click of cancel button
Msgbox "CANCEL CLICKED"
Endif
End Sub
```

