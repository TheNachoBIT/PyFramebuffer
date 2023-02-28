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

	# Print 'Hello' in the top left corner of the screen.
	f.PrintText(0, 2, "Hello")

	# Print a character in the middle of the screen.
	f.PrintAt(int(f.width / 2), int(f.height / 2), ',')

	# Print 'World!' in the bottom right corner of the screen.
	f.PrintText(f.width - 1 - (len("World!")), f.height - 2, "World!")

	f.Draw()
```

Easy as that! :D
