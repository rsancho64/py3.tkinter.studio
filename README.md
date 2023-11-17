# tkinter.studio/

## refs

https://docs.python.org/es/3/library/tkinter.html

## install

py3. [recipe-intro](https://tecadmin.net/how-to-install-python-tkinter-on-linux/) 

### install.test

`python3 -m tkinter` # test0  
`touch test1.py`

```py
from tkinter import *
window=Tk()
lbl=Label(window, text="Welcome to Tecadmin.net", font=("Helvetica", 16))
lbl.place(x=60, y=50)
window.title('Hello Python')
window.geometry("400x150+10+10")
window.mainloop()
```

## mwe's

