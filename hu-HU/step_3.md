## A véletlenszám-generátor modul használata

Eddig te magad választottad ki a véletlen számokat, de megkérheted a számítógépet, hogy válassza ki őket helyetted.

\--- task \---

Adj hozzá egy új `import` sort a programod tetején, az `import SenseHat` alá:

```python
from random import randint
```

\--- /task \---

\--- task \---

Most változtasd meg az `x =` és `y =` sorokat, hogy automatikusan válasszanak egy véletlenszerű helyet:

```python
x = randint(0, 7)
y = randint(0, 7)
```

\--- /task \---

\--- task \---

Futtasd a programodat, és egy újabb véletlenszerű pixel fog megjelenni a kijelzőn. A színe ugyanaz lesz, mint amit korábban választottál.

\--- /task \---

\--- task \---

Most változasd meg a színed értékeit így:

```python
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
```

Most a programod automatikusan egy véletlenszerű színt fog választani.

\--- /task \---

\--- task \---

Futtasd újra, és most egy újabb pixel fog megjelenni egy véletlenszerű helyen véletlenszerű színnel.

\--- /task \---

\--- task \---

Futtasd még néhányszor, így a rács egyre nagyobb része lesz kitöltve a véletlenszerű pixelekkel.

\--- /task \---