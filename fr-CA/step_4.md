## En utilisant le module aléatoire "random"

Jusqu'à présent, vous avez choisi vos propres nombres aléatoires mais vous pouvez laisser l'ordinateur les choisir à votre place.

1. Ajoutez une autre ligne `import` au haut de votre programme, sous `import SenseHat`:
    
    ```python
    from random import randint
    ```

2. Maintenant, changez vos lignes `x=` et `y =` pour choisir une position aléatoire automatiquement:
    
    ```python
    x = randint(0, 7)
    y = randint(0, 7)
    ```

3. Exécutez votre programme à nouveau et vous devriez voir un autre pixel aléatoire apparaître sur l'affichage. Il sera de la même couleur que vous avez choisie précédemment.

4. À présent, changez les lignes déterminant les valeurs de la couleur à:
    
    ```python
    r = randint(0, 255)
    v = randint(0, 255)
    b = randint(0, 255)
    ```

    Votre programme choisira automatiquement une couleur aléatoire.

5. Exécutez le à nouveau et vous devriez voir un autre pixel d'une couleur aléatoire apparaître à une position aléatoire.

6. Exécutez le quelques fois de plus et vous devriez voir l'affichage se remplir progressivement de pixels aléatoires.
