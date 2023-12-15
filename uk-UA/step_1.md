## Вступ

Зроби, щоб твій Sense HAT сяяв гордістю.

--- collapse ---
---
title: Що тобі знадобиться
---

- Комп'ютер Raspberry Pi
- Sense HAT

    Тобі треба буде встановити Mu. Відкрий вікно терміналу і введи наступну команду:

    ```bash
    sudo apt install mu-editor
    ```

або:

- Персональний комп’ютер

Якщо в тебе є Raspberry Pi, але немає Sense HAT, ти можеш використовувати емулятор Sense HAT в Raspbian. Просто на початку свого коду заміни цей рядок import:

`from sense_hat import SenseHat`

на:

`from sense_emu import SenseHat`

Якщо в тебе немає Raspberry Pi, можна використовувати онлайн-емулятор Trinket Sense HAT на [trinket.io/sense-hat](https://trinket.io/sense-hat). Рядок import залишається таким же.

--- /collapse ---

--- collapse ---
---
title: Що ти вивчиш
---

- Керування кольорами світлодіодів (LED) на Sense HAT
- Кольори RGB
- Цикли та ітерації
- Випадковість

--- /collapse ---

--- no-print ---

--- collapse ---
---
title: Інформація для організаторів Jam
---

Якщо вам потрібно роздрукувати цей проєкт, існує [версія PDF](https://github.com/raspberrypilearning/jam-worksheets/raw/master/pdf/Sense-HAT-Random-Sparkles.pdf). Будь ласка, дотримуйтеся інструкцій на цій сторінці перед друком.

--- /collapse ---

--- /no-print ---
