## De random module gebruiken

Tot nu toe heb je je eigen willekeurige nummers gekozen, maar je kunt ze ook door de computer laten kiezen.

--- task ---

Voeg nog een `import` regel toe bovenaan je programma, onder `import SenseHat`:

```python
from random import randint
```

--- /task ---

--- task ---

Verander nu je `x =` en `y =` regels om automatisch een willekeurige positie te selecteren:

```python
x = randint (0, 7)
y = randint (0, 7)
```

--- /task ---

--- task ---

Voer je programma opnieuw uit en er zal een andere willekeurige pixel op het scherm oplichten. Het is dezelfde kleur die je eerder hebt gekozen.

--- /task ---

--- task ---

Verander nu de code waar je de kleurwaarde toekent naar:

```python
r = randint (0, 255)
g = randint (0, 255)
b = randint (0, 255)
```

Nu selecteert je programma automatisch een willekeurige kleur.

--- /task ---

--- task ---

Voer het opnieuw uit en je zou een andere pixel op een willekeurige locatie met een willekeurige kleur moeten zien verschijnen.

--- /task ---

--- task ---

Voer het nog een paar keer uit, en je zou meer van het raster moeten zien vollopen met willekeurige pixels.

--- /task ---