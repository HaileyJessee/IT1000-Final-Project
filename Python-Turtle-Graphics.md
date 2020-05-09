# Python Turtle Graphics

My favorite project I have done in this class was when we worked with Python to create a [*spiorgraph*](https://en.wikipedia.org/wiki/Spirograph)
Here is my block of code I used to create a Pink and Blue spirographic using Turtle Graphics. I loved doing this because I loved the aspect of logic behind the creative process of things. I Feel like I am equal balance of left and right brain meaning I am a logical thinker but I also love to think outside of the box and do something creative.

```Python
>>> from turtle import *
>>> color('blue', 'pink')
>>> begin_fill()
>>> while True:
	forward(300)
	left(150)
	if abs(pos() ) < 1:
		break

	
>>> end_fill()
>>> done()
```

[Home](https://github.com/HaileyJessee/IT1000-Final-Project)
