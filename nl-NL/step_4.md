## Voeg een lus toe

In plaats van je programma zelf te blijven uitvoeren, kan je een lus toevoegen zodat het automatisch blijft lopen.

--- task ---

Voeg eerst een `import` toe bovenaan je bestand:

```python
from time import sleep
```

Je gebruikt dit om het programma tussen de pixels door te pauzeren.

--- /task ---

--- task ---

Voeg een `while True:` toe aan je code, zodat de willekeurige regels, `set_pixel` en `slaap` zich allemaal binnen de lus bevinden:

```python
x = randint(0, 7)
y = randint(0, 7)
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
sense.set_pixel(x, y, r, g, b)
sleep(0.1)
```

--- /task ---

--- task ---

Voer de code uit en je zou willekeurige flikkeringen moeten zien!

--- /task ---

--- task ---

Probeer de slaaptijd te veranderen om deze nog korter te maken.

--- /task ---


**Door de community geleverde vertaling**

Dit project werd vertaald door **Cor Groot**/**Coen Warries** en gecontroleerd door **Bino Maiheu**/**Robert-Jan Kempenaar**.

Onze geweldige vertalers helpen ons om kinderen over de hele wereld de kans te geven te leren coderen. Jij kunt ons helpen nog meer kinderen te bereiken door onze projecten te vertalen - lees meer op [rpf.io/translators](https://rpf.io/translators).