## Hurok hozzáadása

Ahelyett, hogy folyamatosan futnod kell a programodat, hozzáadhatsz egy ciklust, hogy megmaradjon.

1. Először, adj hozzá egy `import` a fájl tetejére:
    
    ```python
az importálás időpontjától
```

Ezt a programot a képpontok közötti szüneteltetésre használja.

2. Add hozzá `while True:` hogy a véletlen sorok, `set_pixel` és `alvás` mind a hurokban vannak:
    
    ```python
míg a True: x = randint (0, 7) y = regiszter (0, 7) r = regiszter (0, 255) g = randint (0, 255) b = regiszter (0, 255) sense.set_pixel , r, g, b) alvás (0,1)
```

3. Futtassa a kódot, és véletlenszerű csillogásokat kell látnia a cselekvésben!

4. Próbálja meg megváltoztatni az alvási időt, hogy még rövidebb legyen.