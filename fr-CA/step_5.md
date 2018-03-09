## Ajouter une boucle

Plutôt que d'avoir à exécuter votre programme à de nombreuses reprises, vous pouvez ajouter une boucle pour qu'il continue à s'exécuter de lui même.

1. D'abord, ajoutez un autre `import` au haut de votre fichier:
    
    ```python
    from time import sleep
    ```

    Vous l'utiliserez pour faire une pause entre l'apparition des pixels.

2. Ajoutez une boucle `while` à votre code pour que les lignes aléatoires, `set_pixel` et `sleep` soient toutes à l'intérieur de la boucle:
    
    ```python
    while True:
        x = randint(0, 7)
        y = randint(0, 7)
        r = randint(0, 255)
        v = randint(0, 255)
        b = randint(0, 255)
        sense.set_pixel(x, y, r, v, b)
        sleep(0.1)
    ```

3. Exécutez votre code et vous devriez voir des scintillements aléatoires en action!

4. Essayez de changer le temps de pause pour le rendre encore plus court.
