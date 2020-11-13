## Füge eine Schleife hinzu

Anstatt dein Programm immer wieder ausführen zu müssen, kannst du eine Schleife hinzufügen, damit es automatisch weiterläuft.

--- task ---

Füge eine weitere `import` Zeile am Anfang deines Programms hinzu, unter `import SenseHat`:

```python
from time import sleep
```

Das verwendest du, um das Programm zwischen den Pixeln kurz anzuhalten.

--- /task ---

--- task ---

Füge ein `while True:` zu deinem Code hinzu, so dass die Zeilen mit den Zufallswerten, `set_pixel` und `sleep` alle innerhalb der Schleife sind:

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

Führe den Code aus und du solltest zufälliges Funkeln in Aktion sehen!

--- /task ---

--- task ---

Versuche, die Pausenzeit zu ändern, um sie noch kürzer zu machen.

--- /task ---
