## Füge eine Schleife hinzu

Anstatt dein Programm immer wieder laufen zu lassen, kannst du eine Schleife hinzufügen, damit es automatisch weiterläuft.

1. Füge zunächst ein `import` am Anfang deiner Datei hinzu:
    
    ```python
from time import sleep
```

Das verwendest du, um das Programm zwischen den Pixeln kurz anzuhalten.

2. Füge ein `while True:` zu deinem Code hinzu, so dass die Zeilen mit den Zufallswerten, `set_pixel` und `sleep` alle innerhalb der Schleife sind:
    
    ```python
while True:
    x = randint(0, 7)
    y = randint(0, 7)
    r = randint(0, 255)
    g = randint(0, 255)
    b = randint(0, 255)
    sensoren.set_pixel(x, y, r, g, b)
    sleep(0.1)
```

3. Führe den Code aus und du solltest zufälliges Funkeln in Aktion sehen!

4. Versuche, die Pausenzeit zu ändern, um sie noch kürzer zu machen.