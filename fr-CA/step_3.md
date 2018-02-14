## Utiliser set_pixel

D'abord, nous allons penser à des nombres aléatoires et utiliser la fonction `set_pixel` pour afficher une couleur aléatoire à un emplacement aléatoire sur l'écran du Sense HAT.

1. Si vous utilisez une Raspberry Pi, ouvrez Python 3 et créez un nouveau fichier. Si vous utilisez l'émulateur web, effacez le code de démonstration avant de débuter.

2. Dans le nouveau fichier, commencez par importer le module Sense HAT.
    
    Si vous utilisez un vrai Sense HAT ou l'émulateur Trinket, la ligne pour importer le module est:
    
    ```python
from sense_hat import SenseHat
```

Si vous utilisez l'émulateur de bureau, la ligne pour importer le module est:

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

6. Pensez à trois nombres aléatoires entre 0 et 255, puis assignez-les à `r`, `v`, et `b`:
    
    ```python
r = 19
v = 180
b = 230
```

7. Utilisez maintenant la fonction `set_pixel` pour afficher votre couleur aléatoire à l'emplacement aléatoire que vous avez défini sur l'affichage:
    
    ```python
sense.set_pixel(x, y, r, v, b)
```

8. Maintenant, exécutez votre code en appuyant sur **F5** (ou le bouton **Run** dans Trinket). Vous devriez voir un seul pixel s'allumer.

9. Choisissez maintenant de nouveaux nombres aléatoires - changez-les tous et réexécutez le programme. Un deuxième pixel devrait apparaître sur l'affichage!