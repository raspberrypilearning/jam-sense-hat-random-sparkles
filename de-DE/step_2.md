## set_pixel verwenden

Zuerst überlegen wir uns einige Zufallszahlen und verwenden die `set_pixel` Funktion, um eine zufällige Farbe an einer zufälligen Stelle auf dem Sense HAT-Display zu platzieren.

--- task ---

Wenn du einen Raspberry Pi verwendest, öffne **Mu**, um zu beginnen. Wenn du den Webemulator verwendest, lösche den Beispielcode, bevor du beginnst.

--- /task ---

--- task ---

Beginne in der neuen Datei mit dem Import des Sense HAT-Moduls.

Wenn du einen echten Sense-HAT oder den Trinket-Emulator verwendest, lautet die Importzeile:

```python
from sense_hat import SenseHat
```

Wenn du den Desktop-Emulator verwendest, lautet die Importzeile:

```python
from sense_emu import SenseHat
```

Der Rest des Codes ist für alle Versionen identisch.

--- /task ---

--- task ---

Erstelle als Nächstes eine Verbindung zu deinem Sense-HAT, indem du Folgendes hinzufügst:

```python
sense = SenseHat()
```

--- /task ---

--- task ---

Denke nun an eine Zufallszahl zwischen 0 und 7 und weise diese der Variablen `x` zu, zum Beispiel:

```python
x = 4
```

--- /task ---

--- task ---

Denke an eine andere Zufallszahl zwischen 0 und 7 und weise sie dann `y` zu:

```python
y = 5
```

--- /task ---

--- task ---

Denke dir drei Zufallszahlen zwischen 0 und 255 aus und weise sie dann `r`, `g` und `b` zu:

```python
r = 19
g = 180
b = 230
```

--- /task ---

--- task ---

Verwende nun die `set_pixel` Funktion, um deine zufällige Farbe an deinem zufälligen Ort auf dem Display zu platzieren:

```python
sense.set_pixel(x, y, r, g, b)
```

--- /task ---

--- task ---

Führe nun deinen Code mit der Schaltfläche **Run** aus. Du solltest ein einzelnes Pixel aufleuchten sehen.

--- /task ---

--- task ---

Wähle nun einige neue Zufallszahlen - ändere sie alle - und führe das Programm erneut aus. Ein anderes Pixel sollte auf dem Display erscheinen!

--- /task ---
