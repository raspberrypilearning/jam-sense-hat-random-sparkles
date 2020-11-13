## Das random-Modul (Zufallsmodul) verwenden

Bis jetzt hast du deine eigenen Zufallszahlen gewählt, aber du kannst sie stattdessen vom Computer wählen lassen.

--- task ---

Füge eine weitere `import` -Zeile am Anfang deines Programms unter der `import SenseHat`-Zeile hinzu:

```python
from random import randint
```

--- /task ---

--- task ---

Ändere nun deine `x =` und `y =` Zeilen, um automatisch eine zufällige Position auszuwählen:

```python
x = randint(0, 7)
y = randint(0, 7)
```

--- /task ---

--- task ---

Führe dein Programm erneut aus, und du solltest ein anderes beliebiges Pixel sehen, das auf dem Display platziert wird. Es wird die gleiche Farbe haben, die du zuvor gewählt hast.

--- /task ---

--- task ---

Ändere nun deine Farbwertzeilen in:

```python
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
```

Jetzt wählt dein Programm automatisch eine zufällige Farbe.

--- /task ---

--- task ---

Führe es erneut aus, und du solltest ein Pixel an einem zufälligen Ort mit einer zufälligen Farbe aufleuchten sehen.

--- /task ---

--- task ---

Führe es noch ein paar Mal aus, und du solltest sehen, dass sich das Display mit zufälligen Pixeln füllt.

--- /task ---
