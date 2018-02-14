## Verwenden von set_pixel

Zuerst überlegen wir uns einige Zufallszahlen und verwenden die `set_pixel` Funktion, um eine zufällige Farbe an einer zufälligen Stelle auf der Sense HAT-Anzeige zu platzieren.

1. Wenn Sie einen Raspberry Pi verwenden, öffnen Sie Python 3 und erstellen Sie eine neue Datei. Wenn Sie den Webemulator verwenden, löschen Sie den Beispielcode, bevor Sie beginnen.

2. Beginnen Sie in der neuen Datei mit dem Import des Sense HAT-Moduls.
    
    Wenn Sie einen echten Sense-HAT oder den Trinket-Emulator verwenden, lautet die Importzeile:
    
    ```python
von sense_hat importieren SenseHat
```

Wenn Sie den Desktop-Emulator verwenden, lautet die Importzeile:

```python
von sense_emu importieren SenseHat
```

Der Rest des Codes wird für alle Versionen identisch sein.

3. Erstellen Sie als Nächstes eine Verbindung zu Ihrer Sense-HAT, indem Sie Folgendes hinzufügen:
    
    ```python
Sinn = SinnHat ()
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