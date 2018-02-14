## Véletlenszerű modul használata

Eddig kiválasztottad a saját véletlen számadatát, de hagyd, hogy a számítógép helyett inkább azokat válassza.

1. Új 123_6_0_321 | import</code> hozzáadása sor a program tetején, alább `import SenseHat`:
    
    ```python
a véletlenszerű importálásból
```

2. Most módosítsa a `x =` és `y =` sorok automatikus véletlen helyzet kiválasztásához:
    
    ```python
x = regiszter (0, 7) y = regiszter (0, 7)
```

3. Futtassa újra a programot, és látnia kell egy másik véletlen pixelet a kijelzőn. Ugyanaz lesz a színe, amelyet korábban választott.

4. Most módosítsa színértéksorjait:
    
    ```python
r = regiszter (0, 255) g = regiszter (0, 255) b = regiszter (0, 255)
```

Most a program automatikusan kiválasztja a véletlenszerű színt.

5. Futtassa újra, és egy véletlenszerű színű véletlenszerű helyen jelenjen meg egy másik pixel.

6. Futtasd még néhányszor, és látnod kell, hogy a rács nagyobb része véletlen pixelekkel tölti fel.