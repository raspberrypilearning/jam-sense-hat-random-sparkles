## Utiliser set_pixel

D'abord, nous allons penser à des nombres aléatoires et utiliser le fonction `set_pixel` pour placer une couleur aléatoire sur un emplacement aléatoire sur l'écran Sense HAT.

1. Si vous utilisez un Raspberry Pi, ouvrez Python 3 et créez un nouveau fichier. Si vous utilisez l'émulateur Web, supprimez l'exemple de code avant de commencer.

2. Dans le nouveau fichier, commencez par importer le module Sense HAT.
    
    Si vous utilisez un vrai Sense HAT ou l'émulateur Trinket, la ligne d'import est:
    
    ```python
from sense_hat import SenseHat
```

Si vous utilisez l'émulateur de bureau, la ligne d'import est:

```python
from sense_emu import SenseHat
```

Le reste du code sera identique pour toutes les versions.

3. Ensuite, créez une connexion à votre Sense HAT en ajoutant:
    
    ```python
sense = SenseHat()
```

4. Pensez maintenant à un nombre aléatoire compris entre 0 et 7 et attribuez-le à la variable `x`, par exemple:
    
    ```python
x = 4
```

5. Pensez à un autre nombre aléatoire compris entre 0 et 7, puis attribuez-le à `y`:
    
    ```python
y = 5
```

6. Pensez à trois nombres aléatoires entre 0 et 255, puis assignez-les à `r`, `g`, et `b`:
    
    ```python
r = 19
g = 180
b = 230
```

7. Utilisez maintenant le fonction `set_pixel` pour placer votre couleur aléatoire à votre emplacement aléatoire sur l'affichage:
    
    ```python
sense.set_pixel(x, y, r, g, b)
```

8. Maintenant, lancez votre code en appuyant sur **F5** (ou le bouton **Run** dans Trinket). Vous devriez voir qu'un seul pixel s'allume.

9. Choisissez maintenant de nouveaux nombres aléatoires - changez-les tous - et réexécutez le programme. Un deuxième pixel devrait apparaître sur l'affichage!