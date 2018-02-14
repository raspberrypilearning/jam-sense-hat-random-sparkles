## Verwenden des Zufallsmoduls

Bis jetzt haben Sie Ihre eigenen Zufallszahlen ausgewählt, aber Sie können den Computer stattdessen wählen lassen.

1. Fügen Sie ein weiteres `import` hinzu Zeile an der Spitze deines Programms, unten `import SenseHat`:
    
    ```python
aus dem Zufalls-Import randint
```

2. Ändern Sie nun Ihre `x =` und `y =` Zeilen, um automatisch eine zufällige Position auszuwählen:
    
    ```python
x = randint (0, 7) y = randint (0, 7)
```

3. Führen Sie Ihr Programm erneut aus, und Sie sollten ein anderes beliebiges Pixel sehen, das auf dem Display platziert wird. Es wird die gleiche Farbe sein, die Sie zuvor gewählt haben.

4. Ändern Sie nun Ihre Farbwertzeilen in:
    
    ```python
r = randint (0, 255) g = randint (0, 255) b = randint (0, 255)
```

Jetzt wählt Ihr Programm automatisch eine zufällige Farbe.

5. Führen Sie es erneut aus, und Sie sollten ein anderes Pixel an einem zufälligen Speicherort mit einer zufälligen Farbe angezeigt werden.

6. Führen Sie es noch ein paar Mal aus, und Sie sollten sehen, dass mehr Gitter mit zufälligen Pixeln gefüllt sind.