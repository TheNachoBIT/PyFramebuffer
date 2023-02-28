# PyFramebuffer
Console Framebuffer for Python

## Get Started

**PyFramebuffer** is only one single .py file, so you can just drag "Framebuffer.py" to your project easily without any installation process!

If you're starting a project with this, you can instantiate a Framebuffer with:

```py
f = Framebuffer()
```

and start drawing stuff in a `while` loop:

```py
from Framebuffer import Framebuffer

f = Framebuffer()

while 1:
	f.PrintAt(0, 2, "Hello")
	f.PrintAt(f.width - 1 - (len("World!") * 2), f.height - 2, "World!")

	f.Draw()
```

Easy as that! :D
