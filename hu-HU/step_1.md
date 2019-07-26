## Bevezetés

Tedd büszkén ragyogóvá a Sense HAT-et.

\--- collapse \---

* * *

## title: Amire szükséged lesz

- Raspberry Pi számítógép
- Sense HAT
    
    Fel kell telepítened a Mu-t. Nyiss meg egy Terminál ablakot, majd írd be az alábbi parancsot:
    
    ```bash
    sudo apt install mu-editor
    ```

vagy:

- PC

Ha van Raspberry Pi-od, de nincs Sense HAT-ed, használhatod a Sense HAT emulátort a Raspbianen. Változtasd meg az első sort a kódodban erről:

`from sense_hat import SenseHat`

erre:

`from sense_emu import SenseHat`.

Ha nincs Raspberry Pi-od, használhatod az online Trinket Sense HAT emulátort itt: [trinket.io/sense-hat](https://trinket.io/sense-hat). Az import sor ugyanaz.

\--- /collapse \---

\--- collapse \---

* * *

## title: Amit meg fogsz tanulni

- Színes LED-ek vezérlése a Sense HAT-en
- RGB-színek
- Ciklusok és ismétlés
- Véletlen számok generálása

\--- /collapse \---

\--- collapse \---

* * *

## title: Információ Jam szervezőknek

\--- no-print \---

Ha ki kell nyomtatnod a projektet, elérhető egy [PDF verzió](https://github.com/raspberrypilearning/jam-worksheets/raw/master/pdf/Sense-HAT-Random-Sparkles.pdf). Olvass el minden megjegyzést ezen az oldalon a nyomtatás előtt.

\--- /no-print \---

\--- /collapse \---