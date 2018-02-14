## A set_pixel használata

Először megvizsgáljuk a véletlen számokat, és használjuk a `set_pixel` hogy véletlenszerű színt helyezzen el egy véletlenszerű helyre a Sense HAT kijelzőn.

1. Ha Raspberry Pi-et használ, nyissa meg a Python 3-ot és hozzon létre egy új fájlt. Ha webes emulátort használ, akkor törölje a példakódot, mielőtt elkezdené.

2. Az új fájlban indítsa el a Sense HAT modul importálásával.
    
    Ha valódi Sense HAT-ot vagy Trinket-emulátort használ, az importvonal a következő:
    
    ```python
sense_hat import SenseHat
```

Ha az asztali emulert használja, az importvonal a következő:

```python
a sense_emu import SenseHat
```

A többi kód azonos lesz minden változatban.

3. Ezután hozzon létre egy kapcsolatot a Sense HAT-hoz hozzáadva:
    
    ```python
sense = SenseHat ()
```

4. Most gondoljon egy 0 és 7 közötti véletlen számra, és hozzárendelje a változóhoz `x`, például:
    
    ```python
x = 4
```

5. Gondolj egy másik véletlen számra 0 és 7 között, majd rendelje hozzá `y`:
    
    ```python
y = 5
```

6. Gondolj három véletlen számra 0 és 255 között, majd adja hozzá azokat `r`, `g`és `b`:
    
    ```python
r = 19 g = 180 b = 230
```

7. Most használja a `set_pixel` -t funkcióval a véletlenszerű színt elhelyezheti a véletlenszerű helyen a kijelzőn:
    
    ```python
sense.set_pixel (x, y, r, g, b)
```

8. Most futtassa a kódot a **F5** gombbal (vagy a **Run** gomb a Trinketben). Egy pixeles fényt kell látnia.

9. Most válasszon néhány új véletlen számot - mindet megváltoztassa - és futtassa újra a programot. Egy második pixel jelenik meg a kijelzőn!