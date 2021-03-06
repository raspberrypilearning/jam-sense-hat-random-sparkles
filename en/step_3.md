## Using the random module

So far you've picked your own random numbers, but you can let the computer choose them instead.

--- task ---

Add another `import` line at the top of your program, below `import SenseHat`:

```python
from random import randint
```

--- /task ---

--- task ---

Now change your `x =` and `y =` lines to automatically select a random position:

```python
x = randint(0, 7)
y = randint(0, 7)
```

--- /task ---

--- task ---

Run your program again, and you should see another random pixel being placed on the display. It will be the same colour you chose previously.

--- /task ---

--- task ---

Now change your colour value lines to:

```python
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
```

Now your program will automatically select a random colour.

--- /task ---

--- task ---

Run it again, and you should see another pixel appear in a random location with a random colour.

--- /task ---

--- task ---

Run it a few more times, and you should see more of the grid fill up with random pixels.

--- /task ---
