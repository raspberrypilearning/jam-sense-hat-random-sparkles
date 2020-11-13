## Usando set_pixel

Primero, crearás algunos números aleatorios y usarás la función `set_pixel` para colocar un color aleatorio en una ubicación aleatoria en la pantalla del Sense HAT.

--- task ---

Si estás usando una Raspberry Pi, abre **Mu** para empezar. Si estás utilizando el emulador web, elimina el código de ejemplo antes de comenzar.

--- /task ---

--- task ---

En el nuevo archivo, comienza importando el módulo Sense HAT.

Si estás utilizando un Sense HAT real o el emulador Trinket, la línea de importación es:

```python
from sense_hat import SenseHat
```

Si está utilizando el emulador de escritorio, la línea de importación es:

```python
from sense_emu import SenseHat
```

El resto del código será idéntico para todas las versiones.

--- /task ---

--- task ---

A continuación, crea una conexión a tu Sense HAT agregando:

```python
sense = SenseHat()
```

--- /task ---

--- task ---

Ahora piensa en un número aleatorio entre 0 y 7 y asígnalo a la variable `x`, por ejemplo:

```python
x = 4
```

--- /task ---

--- task ---

Piensa en otro número aleatorio entre 0 y 7, luego asígnalo a `y`:

```python
y = 5
```

--- /task ---

--- task ---

Piensa en tres números aleatorios entre 0 y 255, luego asígnalos a `r`, `g`y `b`:

```python
r = 19
g = 180
b = 230
```

--- /task ---

--- task ---

Ahora usa la función `set_pixel` para colocar el color aleatorio en una posición aleatoria en la pantalla:

```python
sensor.set_pixel(x, y, r, g, b)
```

--- /task ---

--- task ---

Ahora ejecuta tu código mediante el botón **Run (nota: ejecutar)**. Deberías ver un solo píxel encendido.

--- /task ---

--- task ---

Ahora escoje algunos números aleatorios nuevos - cámbialos todos - y vuelve a ejecutar el programa. ¡Debería aparecer un segundo píxel en la pantalla!

--- /task ---
