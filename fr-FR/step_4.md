## Utiliser le module aléatoire

Jusqu'à présent, vous avez choisi vos propres nombres aléatoires, mais vous pouvez laisser l'ordinateur les choisir à la place.

1. Ajouter un autre ligne d'`import` en haut de votre programme, ci-dessous `import SenseHat`:
    
    ```python
à partir de rand import aléatoire
```

2. Maintenant, changez votre `x =` et `y =` lignes pour sélectionner automatiquement une position aléatoire:
    
    ```python
x = randint (0, 7) y = randint (0, 7)
```

3. Exécutez votre programme à nouveau, et vous devriez voir un autre pixel aléatoire étant placé sur l'affichage. Ce sera la même couleur que vous avez choisi précédemment.

4. Maintenant, changez vos lignes de valeur de couleur à:
    
    ```python
r = randint (0, 255) g = randint (0, 255) b = randint (0, 255)
```

Maintenant, votre programme va automatiquement sélectionner une couleur aléatoire.

5. Exécutez-le à nouveau, et vous devriez voir un autre pixel apparaître dans un endroit aléatoire avec une couleur aléatoire.

6. Exécutez-le quelques fois de plus, et vous devriez voir plus de la grille se remplir de pixels aléatoires.