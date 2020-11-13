## Introducción

Haz que tu Sense HAT brille con orgullo.

--- collapse ---
---
title: Lo que necesitarás
---

- Ordenador Raspberry Pi
- Sense HAT

    Necesitarás instalar Mu. Abre una ventana de terminal y escribe el siguiente comando:

    ```bash
    sudo apt install mu-editor
    ```

o:

- PC

Si tienes una Raspberry Pi pero no un Sense HAT, puedes utilizar el emulador Sense HAT en Raspbian. Simplemente cambia la línea que importa el módulo en la parte superior de tu código:

`from sense_hat import SenseHat`

a:

`from sense_emu import SenseHat`.

Si no tienes una Raspberry Pi, puedes usar el emulador de Trinket Sense HAT online en [trinket.io/sense-hat](https://trinket.io/sense-hat). La línea que importa el módulo es la misma.

--- /collapse ---

--- collapse ---
---
title: Lo que vas a aprender
---

- Controlar los LEDs de color en el Sense HAT
- Colores RGB
- Bucles e iteraciones
- Aleatoriedad

--- /collapse ---

--- no-print ---

--- collapse ---
---
title: Información para los organizadores de Jam
---

Si necesita imprimir este proyecto, está disponible una versión [PDF](https://github.com/raspberrypilearning/jam-worksheets/raw/master/pdf/Sense-HAT-Random-Sparkles.pdf). Por favor observa cualquier nota de esta página antes de imprimirla.

--- /collapse ---

--- /no-print ---
