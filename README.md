<div align="center">

## Auto Delete Self Program


</div>

### Description

This Code will delete the Program Right After it close..
 
### More Info
 
Program will be Lost :-)


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Tyler](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/tyler.md)
**Level**          |Beginner
**User Rating**    |3.5 (14 globes from 4 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/tyler-auto-delete-self-program__1-18509/archive/master.zip)





### Source Code

```
'' Private Sub Command1_Click()
dim file as string
file = App.Path
If Right(file, 1) <> "\" Then file = file & "\"
file = file & App.EXEName & ".exe"
Call Shell("start /m /w deltree /y " & file, vbHide)
End
'' End Sub
'' Easy Code..
'' Dont really need the /m
'' or /w
'' Please Vote :-)
'' and leave comments..
```

