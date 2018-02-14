## Ajouter une boucle

Plutôt que de devoir continuer à exécuter votre programme, vous pouvez ajouter une boucle pour qu'elle continue à fonctionner.

1. D'abord, ajoutez un `import` au début de votre fichier:
    
    ```python
à partir de temps importer le sommeil
```

Vous l'utiliserez pour mettre le programme en pause entre les pixels.

2. Ajoutez un `while True:` à votre code de sorte que les lignes au hasard, `set_pixel` et `sommeil` sont tous dans la boucle:
    
    ```python
alors que vrai: x = randint (0, 7) y = randint (0, 7) r = randint (0, 255) g = randint (0, 255) b = randint (0, 255) sens.set_pixel (x, y , r, g, b) sommeil (0,1)
```

3. Exécutez le code et vous devriez voir des étincelles au hasard en action!

4. Essayez de changer le temps de sommeil pour le rendre encore plus court.