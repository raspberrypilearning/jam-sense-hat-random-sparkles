## Das Zufallsmodul verwenden

Bis jetzt habest du deine eigenen Zufallszahlen gewählt, aber du kannst den Computer stattdessen wählen lassen.

1. Füge eine weitere `import` Zeile am Anfang deines Programms hinzu, unter `import SenseHat`:
    
    ```python
from random import randint
```

2. Ändere nun deine `x =` und `y =` Zeilen, um automatisch eine zufällige Position auszuwählen:
    
    ```python
x = randint(0, 7)
y = randint(0, 7)
```

3. Führe dein Programm erneut aus, und du solltest ein anderes beliebiges Pixel sehen, das auf dem Display platziert wird. Es wird die gleiche Farbe sein, die du zuvor gewählt hast.

4. Ändere nun deine Farbwertzeilen in:
    
    ```python
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
```

Jetzt wählt dein Programm automatisch eine zufällige Farbe.

5. Führe es erneut aus, und du solltest ein Pixel an einem anderen, zufälligen Ort mit einer zufälligen Farbe angezeigt bekommen.

6. Führe es noch ein paar Mal aus, und du solltest sehen, dass sich das Display mit zufälligen Pixeln füllt.