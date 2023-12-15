## Utiliser le module aléatoire

D'abord, nous allons penser à des nombres aléatoires et utiliser la fonction `set_pixel` pour placer une couleur aléatoire sur un emplacement aléatoire sur l'écran Sense Hat.

--- task ---

from sense_hat import SenseHat

```python
from random import randint
```

--- /task ---

--- task ---

Pense maintenant à un nombre aléatoire compris entre 0 et 7 et attribue-le à la variable `x`, par exemple :

```python
x = randint(0, 7)
y = randint(0, 7)
```

--- /task ---

--- task ---

Choisis maintenant de nouveaux nombres aléatoires - change-les tous - et exécute le programme à nouveau. Un deuxième pixel devrait apparaître sur l'affichage ! Ce sera la même couleur que tu as choisie précédemment.

--- /task ---

--- task ---

Maintenant, change tes lignes de valeur de couleur à :

```python
r = randint(0, 255)
g = randint(0, 255)
b = randint(0, 255)
```

Maintenant, ton programme va automatiquement sélectionner une couleur aléatoire.

--- /task ---

--- task ---

Exécute-le à nouveau, et tu devrais voir un autre pixel apparaître dans un endroit aléatoire avec une couleur aléatoire.

--- /task ---

--- task ---

Exécute-le encore plusieurs fois, et tu devrais voir une plus grande partie de la grille se remplir de pixels aléatoires.

--- /task ---
