## Füge eine Schleife hinzu

Anstatt dein Programm immer wieder laufen zu lassen, kannst du eine Schleife hinzufügen, damit es automatisch weiterläuft.

1. Füge zunächst ein `import` am Anfang deiner Datei hinzu:
    
    ```python
from time import sleep
```

Sie verwenden dies, um das Programm zwischen den Pixeln anzuhalten.

2. Fügen Sie ein `while True hinzu:` zu Ihrem Code, so dass die zufälligen Zeilen, `set_pixel` und `sleep` sind alle innerhalb der Schleife:
    
    ```python
wahr: x = randint (0, 7) y = randint (0, 7) r = randint (0, 255) g = randint (0, 255) b = randint (0, 255) sense.set_pixel (x, y , r, g, b) Schlaf (0,1)
```

3. Führen Sie den Code und Sie sollten zufällige Funken in Aktion sehen!

4. Versuchen Sie, die Schlafzeit zu ändern, um sie noch kürzer zu machen.