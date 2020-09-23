<div align="center">

## Accept Only Numbers in Textbox \!


</div>

### Description

Do you want to input only numbers in a textbox? and just want a few lines of code ?Well this code is for you....See it for yourself....Want to know more of my codes then email me....
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mark Anthony Dinglasa](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mark-anthony-dinglasa.md)
**Level**          |Beginner
**User Rating**    |3.8 (15 globes from 4 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mark-anthony-dinglasa-accept-only-numbers-in-textbox__1-51262/archive/master.zip)





### Source Code

```
'In the KeyPress event of a textbox
'Shall we say you have put one textbox in your form
'Here it goes
Private Sub text1_KeyPress(Keyascii as Integer)
Select case Keyascii
case asc(vbcr)
      Keyascii=0
    case 8,46
    case 47 to 58
    case else
      Keyascii=0
End Select
End Sub
```

