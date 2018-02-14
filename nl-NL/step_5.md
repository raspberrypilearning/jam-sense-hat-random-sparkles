## Voeg een lus toe

In plaats van dat u uw programma blijft uitvoeren, kunt u een lus toevoegen zodat deze door kan gaan.

1. Voeg eerst een `import` toe naar de top van uw bestand:
    
    ```python
van tijd importeren slaap
```

U gebruikt dit om het programma tussen de pixels te pauzeren.

2. Voeg een `while True toe:` naar uw code, zodat de willekeurige regels, `set_pixel` en `slaap` zijn allemaal binnen de lus:
    
    ```python
while True: x = randint (0, 7) y = randint (0, 7) r = randint (0, 255) g = randint (0, 255) b = randint (0, 255) sense.set_pixel (x, y , r, g, b) slaap (0,1)
```

3. Voer de code uit en je zou willekeurige sparkles in actie moeten zien!

4. Probeer de slaaptijd te veranderen om deze nog korter te maken.