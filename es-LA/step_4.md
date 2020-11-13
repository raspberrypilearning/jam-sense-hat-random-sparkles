## Añadir un bucle

En lugar de tener que seguir ejecutando repetidamente el programa, puedes agregar un bucle para que continúe el ciclo.

--- task ---

Primero, añade un `import` a la parte superior de tu archivo:

```python
from time import sleep
```

Lo usarás para pausar el programa entre píxeles.

--- /task ---

--- task ---

Añade un `while True:` a tu código para que las líneas aleatorias, `set_pixel` y `sleep` estén dentro del bucle:

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

--- /task ---

--- task ---

¡Ejecuta el código y deberías ver destellos aleatorios en acción!

--- /task ---

--- task ---

Intenta cambiar el tiempo de pausa del programa para que sea aún más corto.

--- /task ---
