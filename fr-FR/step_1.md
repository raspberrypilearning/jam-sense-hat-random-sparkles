## Introduction

Fais briller ton Sense HAT avec fierté.

--- collapse ---
---
title: Ce qu'il te faudra
---

- Un ordinateur Raspberry Pi
- Sense HAT

    Tu vas avoir besoin d'installer Mu. Ouvre la fenêtre du Terminal et tape la commande suivante :

    ```bash
    sudo apt install mu-editor
    ```

ou:

- PC

Si tu as un Raspberry Pi mais pas de Sense HAT, tu peux utiliser l'émulateur Sense HAT dans Raspbian. Change simplement la ligne d'importation en haut de ton code de :

`from sense_hat import SenseHat`

en :

`from sense_emu import SenseHat`.

Si tu n'as pas de Raspberry Pi, tu peux utiliser l'émulateur Trinket Sense HAT en ligne sur [trinket.io/sense-hat](https://trinket.io/sense-hat). La ligne d'importation est la même.

--- /collapse ---

--- collapse ---
---
title: Ce que tu vas apprendre
---

- Le contrôle des LED de couleur sur le Sense HAT
- Les couleurs RVB
- Les boucles et itération
- Aléatoire

--- /collapse ---

--- no-print ---

--- collapse ---
---
title: Informations pour les organisateurs de Jam
---

Si vous avez besoin d'imprimer ce projet, une [version PDF](https://github.com/raspberrypilearning/jam-worksheets/raw/master/pdf/Sense-HAT-Random-Sparkles.pdf) est disponible. Merci de considérer toutes les notes de cette page avant d'imprimer.

--- /collapse ---

--- /no-print ---
