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

4. Denken Sie nun an eine Zufallszahl zwischen 0 und 7 und weisen Sie diese der Variablen `x`zu, zum Beispiel:
    
    ```python
x = 4
```

5. Denken Sie an eine andere Zufallszahl zwischen 0 und 7 und weisen Sie sie dann `y`zu:
    
    ```python
y = 5
```

6. Stellen Sie sich drei Zufallszahlen zwischen 0 und 255 vor und weisen Sie sie dann `r`, `g`und `b`:
    
    ```python
r = 19 g = 180 b = 230
```

7. Verwenden Sie nun die `set_pixel` Funktion, um Ihre zufällige Farbe an Ihrem zufälligen Ort auf dem Display zu platzieren:
    
    ```python
sense.set_pixel (x, y, r, g, b)
```

8. Führen Sie nun Ihren Code aus, indem Sie **F5** (oder die **Run** Schaltfläche in Trinket). Sie sollten ein einzelnes Pixel aufleuchten sehen.

9. Wählen Sie nun einige neue Zufallszahlen - ändern Sie sie alle - und führen Sie das Programm erneut aus. Ein zweites Pixel sollte auf dem Display erscheinen!