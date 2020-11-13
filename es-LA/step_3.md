## Usando el módulo random

Hasta ahora has elegido tus propios números aleatorios, pero puedes dejar que el ordenador los escoja.

--- task ---

Añade otra línea `de importación` en la parte superior de tu programa, debajo de `import SenseHat`:

```python
from random import randint
```

--- /task ---

--- task ---

Ahora cambia tus líneas `x =` e `y =` para que seleccionen automáticamente una posición aleatoria:

```python
x = randint(0, 7)
y = randint(0, 7)
```

--- /task ---

--- task ---

Ejecuta el programa de nuevo, y deberías ver como otro píxel aleatorio está encendido en la pantalla. Será del mismo color que eligiste anteriormente.

--- /task ---

--- task ---

Ahora cambia las líneas que determinan el valor del color a:

```python
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
```

Ahora tu programa seleccionará automáticamente un color aleatorio.

--- /task ---

--- task ---

Vuelve a ejecutarlo, y deberías ver otro píxel encendido en otro lugar aleatorio con un color aleatorio.

--- /task ---

--- task ---

Ejecútalo unas cuantas veces más y deberías ver que más de la cuadrícula se llena con píxeles aleatorios.

--- /task ---
