## Fügen Sie eine Schleife hinzu

Anstatt Ihr Programm weiterlaufen zu lassen, können Sie eine Schleife hinzufügen, damit es weiterläuft.

1. Fügen Sie zunächst ein `import` hinzu an den Anfang Ihrer Datei:
    
    ```python
Von Zeit zu Zeit schlafen
```

Sie verwenden dies, um das Programm zwischen den Pixeln anzuhalten.

2. Fügen Sie ein `while True hinzu:` zu Ihrem Code, so dass die zufälligen Zeilen, `set_pixel` und `sleep` sind alle innerhalb der Schleife:
    
    ```python
wahr: x = randint (0, 7) y = randint (0, 7) r = randint (0, 255) g = randint (0, 255) b = randint (0, 255) sense.set_pixel (x, y , r, g, b) Schlaf (0,1)
```

3. Führen Sie den Code und Sie sollten zufällige Funken in Aktion sehen!

4. Versuchen Sie, die Schlafzeit zu ändern, um sie noch kürzer zu machen.