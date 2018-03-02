## set_pixel verwenden

Zuerst überlegen wir uns einige Zufallszahlen und verwenden die `set_pixel` Funktion, um eine zufällige Farbe an einer zufälligen Stelle auf der Sense HAT-Anzeige zu platzieren.

1. Wenn du einen Raspberry Pi verwendest, öffne Python 3 und erstelle eine neue Datei. Wenn du den Webemulator verwendest, lösche den Beispielcode, bevor du beginnst.

2. Beginne in der neuen Datei mit dem Import des Sense HAT-Moduls.
    
    Wenn du einen echten Sense-HAT oder den Trinket-Emulator verwendest, lautet die Importzeile:
    
    ```python
from sense_hat import SenseHat
```

Wenn du den Desktop-Emulator verwendest, lautet die Importzeile:

```python
from sense_emu import SenseHat
```

Der Rest des Codes ist für alle Versionen identisch.

3. Erstelle als Nächstes eine Verbindung zu deinem Sense-HAT, indem du Folgendes hinzufügst:
    
    ```python
sensoren = SenseHat()
```

4. Denke nun an eine Zufallszahl zwischen 0 und 7 und weise diese der Variablen `x` zu, zum Beispiel:
    
    ```python
x = 4
```

5. Denke an eine andere Zufallszahl zwischen 0 und 7 und weise sie dann `y`zu:
    
    ```python
y = 5
```

6. Denke dir drei Zufallszahlen zwischen 0 und 255 aus und weise sie dann `r`, `g`und `b` zu:
    
    ```python
r = 19
g = 180
b = 230
```

7. Verwende nun die `set_pixel` Funktion, um deine zufällige Farbe an deinem zufälligen Ort auf dem Display zu platzieren:
    
    ```python
sensoren.set_pixel (x, y, r, g, b)
```

8. Führe nun deinen Code aus, indem du **F5** (oder die **Run** Schaltfläche in Trinket) drückst. Du solltest ein einzelnes Pixel aufleuchten sehen.

9. Wähle nun einige neue Zufallszahlen - ändere sie alle - und führe das Programm erneut aus. Ein anderes Pixel sollte auf dem Display erscheinen!