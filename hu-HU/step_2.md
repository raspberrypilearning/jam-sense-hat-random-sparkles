## A set_pixel függvény használata

Először ki fogsz találni néhány véletlen számot, és a `set_pixel` függvény segítségével meg fogsz jeleníteni egy véletlenszerű színt egy véletlenszerű helyen a Sense HAT kijelzőn.

\--- task \---

Ha Raspberry Pi-t használsz, nyisd meg a **Mu**-t a kezdéshez. Ha a webes emulátort használod, a kezdés előtt töröld ki a példakódot.

\--- /task \---

\--- task \---

Az új fájlban kezdésként importáld a Sense HAT modult.

Ha igazi Sense HAT-et vagy a Trinket emulátort használod, az import sor az alábbi:

```python
from sense_hat import SenseHat
```

Ha az asztali emulátort használod, az import sor az alábbi:

```python
from sense_emu import SenseHat
```

A kód többi része mindegyik verziónál ugyanaz.

\--- /task \---

\--- task \---

Ezután nyiss meg egy kapcsolatot a Sense HAT-hez az alábbi kóddal:

```python
sense = SenseHat()
```

\--- /task \---

\--- task \---

Most válassz egy véletlen számot 0 és 7 között, és add értékül az `x` változónak, például:

```python
x = 4
```

\--- /task \---

\--- task \---

Válassz egy másik véletlen számot 0 és 7 között, és add értékül az `y` változónak:

```python
y = 5
```

\--- /task \---

\--- task \---

Válassz 3 véletlen számot 0 és 255 között, és add értékül őket az `r`, `g` és `b` változóknak:

```python
r = 19
g = 180
b = 230
```

\--- /task \---

\--- task \---

Most használd a `set_pixel` függvényt, hogy a véletlenszerű színt a véletlenszerű helyen felvillantsd a kijelzőn:

```python
sense.set_pixel(x, y, r, g, b)
```

\--- /task \---

\--- task \---

Most futtasd a kódodat a **Run** gombbal. Azt kell látnod, hogy felvillan egy pixel.

\--- /task \---

\--- task \---

Most válassz új véletlen számokat - mindegyiket változtasd meg -, majd futtasd újra a programot. Egy második pixel jelenik meg a kijelzőn!

\--- /task \---