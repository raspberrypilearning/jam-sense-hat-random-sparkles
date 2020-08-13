## Add a loop

Rather than have to keep running your program, you can add a loop so that it will keep going.

--- task ---

First, add an `import` to the top of your file:

```python
from time import sleep
```

You'll use this to pause the program between pixels.

--- /task ---

--- task ---

Add a `while True:` to your code so that the random lines, `set_pixel` and `sleep` are all within the loop:

```python
while True:
    x = randint(0, 7)
    y = randint(0, 7)
    r = randint(0, 255)
    g = randint(0, 255)
    b = randint(0, 255)
    sense.set_pixel(x, y, r, g, b)
    sleep(0.1)
```

--- /task ---

--- task ---

Run the code and you should see random sparkles in action!

--- /task ---

--- task ---

Try changing the sleep time to make it even shorter.

--- /task ---
