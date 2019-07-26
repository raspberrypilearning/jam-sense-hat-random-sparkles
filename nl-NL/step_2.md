## Het gebruik van set_pixel

Eerst ga je wat willekeurige getallen bedenken en de `set_pixel` functie gebruiken om een ​​willekeurige kleur op een willekeurige locatie op de Sense HAT display te laten oplichten.

\--- task \---

Als je een Raspberry Pi gebruikt, open **Mu** om te beginnen. Als je de webemulator gebruikt, verwijder voordat je begint de voorbeeldcode.

\--- /task \---

\--- task \---

Begin in het nieuwe bestand met het importeren van de Sense HAT-module.

Als je een echte Sense HAT of de Trinket-emulator gebruikt, is de importregel:

```python
from sense_hat import SenseHat
```

Als je de desktopemulator gebruikt, is de importregel:

```python
from sense_emu import SenseHat
```

De rest van de code is voor alle versies gelijk.

\--- /task \---

\--- task \---

Maak vervolgens een verbinding met je Sense HAT door het volgende toe te voegen:

```python
sense = SenseHat ()
```

\--- /task \---

\--- task \---

Bedenk nu een willekeurig getal tussen 0 en 7 en wijs het toe aan de variabele `x`, bijvoorbeeld:

```python
x = 4
```

\--- /task \---

\--- task \---

Bedenk een ander willekeurig getal tussen 0 en 7 en wijs het toe aan `y`:

```python
y = 5
```

\--- /task \---

\--- task \---

Bedenk drie willekeurige getallen tussen 0 en 255, en wijs ze dan toe aan `r`, `g`, en `b`:

```python
r = 19
g = 180
b = 230
```

\--- /task \---

\--- task \---

Gebruik nu de `set_pixel` functie om de gekozen willekeurige kleur op de willekeurige locatie op het display te plaatsen:

```python
sense.set_pixel (x, y, r, g, b)
```

\--- /task \---

\--- task \---

Voer nu je code uit door de **Run** knop te gebruiken. Je zou één enkele pixel moeten zien oplichten.

\--- /task \---

\--- task \---

Kies nu een aantal nieuwe willekeurige nummers - verander ze allemaal - en voer het programma opnieuw uit. Een tweede pixel zou op het display moeten verschijnen!

\--- /task \---