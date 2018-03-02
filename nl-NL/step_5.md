## Voeg een lus toe

In plaats van je programma zelf te blijven uitvoeren, kan je een lus toevoegen zodat het automatisch blijft lopen.

1. Voeg eerst een `import` toe bovenaan je bestand:
    
    ```python
from time import sleep
```

Je gebruikt dit om het programma tussen de pixels door te pauzeren.

2. Voeg een `while True:` toe aan je code, zodat de willekeurige regels, `set_pixel` en `slaap` zich allemaal binnen de lus bevinden:
    
    ```python
x = randint(0, 7)
y = randint(0, 7)
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
sense.set_pixel(x, y, r, g, b)
sleep(0.1)
```

3. Voer de code uit en je zou willekeurige flikkeringen moeten zien!

4. Probeer de slaaptijd te veranderen om deze nog korter te maken.