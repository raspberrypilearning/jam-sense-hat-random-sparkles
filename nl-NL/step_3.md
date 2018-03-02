## Het gebruik van set_pixel

Eerst zullen we wat willekeurige getallen bedenken en de `set_pixel` functie gebruiken om een ​​willekeurige kleur op een willekeurige locatie op de Sense HAT display te laten oplichten.

1. Als je een Raspberry Pi gebruikt, open dan Python 3 en maak een nieuw bestand aan. Als je de webemulator gebruikt, verwijder voordat je begint de voorbeeldcode.

2. Begin in het nieuwe bestand met het importeren van de Sense HAT-module.
    
    Als je een echte Sense HAT of de Trinket-emulator gebruikt, is de importregel:
    
    ```python
from sense_hat import SenseHat
```

Als je de desktopemulator gebruikt, is de importregel:

```python
from sense_emu import SenseHat
```

De rest van de code is voor alle versies gelijk.

3. Maak vervolgens een verbinding met je Sense HAT door het volgende toe te voegen:
    
    ```python
sense = SenseHat ()
```

4. Bedenk nu een willekeurig getal tussen 0 en 7 en wijs het toe aan de variabele `x`, bijvoorbeeld:
    
    ```python
x = 4
```

5. Bedenk een ander willekeurig getal tussen 0 en 7 en wijs het toe aan `y`:
    
    ```python
y = 5
```

6. Bedenk drie willekeurige getallen tussen 0 en 255, en wijs ze dan toe aan `r`, `g`, en `b`:
    
    ```python
r = 19
g = 180
b = 230
```

7. Gebruik nu de `set_pixel` functie om de gekozen willekeurige kleur op de willekeurige locatie op het display te plaatsen:
    
    ```python
sense.set_pixel (x, y, r, g, b)
```

8. Voer nu je code uit door op **F5** te drukken (of de **Run** knop in Trinket). Je zou één enkele pixel moeten zien oplichten.

9. Kies nu een aantal nieuwe willekeurige nummers - verander ze allemaal - en voer het programma opnieuw uit. Een tweede pixel zou op het display moeten verschijnen!