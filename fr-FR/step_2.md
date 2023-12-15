## Utiliser set_pixel

D'abord, nous allons penser à des nombres aléatoires et utiliser le fonction `set_pixel` pour placer une couleur aléatoire sur un emplacement aléatoire sur l'écran Sense HAT.

--- task ---

Si tu utilises un Raspberry Pi, ouvre **Mu** pour commencer. Si tu utilises l'émulateur Web, supprime l'exemple de code avant de commencer.

--- /task ---

--- task ---

Dans le nouveau fichier, commence par importer le module Sense HAT.

Si tu utilises un vrai Sense HAT ou l'émulateur Trinket, la ligne d'import est:

```python
from sense_hat import SenseHat
```

Si tu utilises l'émulateur de bureau, la ligne d'import est:

```python
from sense_emu import SenseHat
```

Le reste du code sera identique pour toutes les versions.

--- /task ---

--- task ---

Ensuite, crée une connexion à votre Sense HAT en ajoutant :

```python
Sense HAT
```

--- /task ---

--- task ---

Pense maintenant à un nombre aléatoire compris entre 0 et 7 et attribue-le à la variable `x`, par exemple :

```python
x = 4
```

--- /task ---

--- task ---

Pense à un autre nombre aléatoire compris entre 0 et 7, puis attribue-le à `y` :

```python
y = 5
```

--- /task ---

--- task ---

Pense à trois nombres aléatoires entre 0 et 255, puis assigne-les à `r`, `g`, et `b` :

```python
r = 19
g = 180
b = 230
```

--- /task ---

--- task ---

Utilise maintenant la fonction `set_pixel` pour placer ta couleur aléatoire à ton emplacement aléatoire sur l'affichage :

```python
sense.set_pixel(x, y, r, g, b)
```

--- /task ---

--- task ---

Exécute maintenant ton code par le bouton **Run**. Tu devrais voir qu'un seul pixel s'allume.

--- /task ---

--- task ---

Choisis maintenant de nouveaux nombres aléatoires - change-les tous - et exécute le programme à nouveau. Un deuxième pixel devrait apparaître sur l'affichage !

--- /task ---
