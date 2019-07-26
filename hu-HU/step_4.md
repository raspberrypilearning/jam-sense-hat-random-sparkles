## Adj hozzá egy ciklust

Ahelyett, hogy újra és újra kézzel kelljen elindítanod a programodat, hozzáadhatsz egy ciklust, hogy folyamatosan menjen.

\--- task \---

Először adj hozzá egy `import` sort a fájlod tetejére:

```python
from time import sleep
```

Ezt fogod használni, hogy a program várakozzon a pixelek között.

\--- /task \---

\--- task \---

Adj hozzá egy `while True:` sort a kódodhoz, hogy a `set_pixel` and `sleep` sorok benne legyenek a ciklusban:

```python
while True:
    x = randint(0, 7)
    y = randint(0, 7)
    r = randint(0, 255)
    g = randint(0, 255)
    b = randint(0, 255)
    sense.set_pixel(x, y, r, g, b)
    sleep(0.1)
```

\--- /task \---

\--- task \---

Futtasd a kódot, és láthatod a véletlenszerű ragyogást!

\--- /task \---

\--- task \---

Próbáld megváltoztatni a várakozási időt a sleep függvényben, hogy még rövidebb legyen.

\--- /task \---