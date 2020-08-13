## Using set_pixel

First, you'll think up some random numbers and use the `set_pixel` function to place a random colour on a random location on the Sense HAT display.

--- task ---

If you're using a Raspberry Pi, open **Mu** to start. If you're using the web emulator, delete the example code before you begin.

--- /task ---

--- task ---

In the new file, start by importing the Sense HAT module.

If you're using a real Sense HAT or the Trinket emulator, the import line is:

```python
from sense_hat import SenseHat
```

If you're using the desktop emulator, the import line is:

```python
from sense_emu import SenseHat
```

The rest of the code will be identical for all versions.

--- /task ---

--- task ---

Next, create a connection to your Sense HAT by adding:

```python
sense = SenseHat()
```

--- /task ---

--- task ---

Now think of a random number between 0 and 7 and assign it to the variable `x`, for example:

```python
x = 4
```

--- /task ---

--- task ---

Think of another random number between 0 and 7, then assign it to `y`:

```python
y = 5
```

--- /task ---

--- task ---

Think of three random numbers between 0 and 255, then assign them to `r`, `g`, and `b`:

```python
r = 19
g = 180
b = 230
```

--- /task ---

--- task ---

Now use the `set_pixel` function to place your random colour at your random location on the display:

```python
sense.set_pixel(x, y, r, g, b)
```

--- /task ---

--- task ---

Now run your code by the **Run** button. You should see a single pixel light up.

--- /task ---

--- task ---

Now pick some new random numbers - change them all - and run the program again. A second pixel should appear on the display!

--- /task ---
