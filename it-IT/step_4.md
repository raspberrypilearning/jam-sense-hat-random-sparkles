## Usando il modulo casuale

Finora hai scelto i tuoi numeri casuali, ma puoi lasciare che siano i computer a sceglierli.

1. Aggiungi un altro `import` riga nella parte superiore del tuo programma, sotto `import SenseHat`:
    
    ```python
da randint di importazione casuale
```

2. Ora modifica il tuo `x =` e `y =` linee per selezionare automaticamente una posizione casuale:
    
    ```python
x = randint (0, 7) y = randint (0, 7)
```

3. Esegui nuovamente il programma e dovresti vedere un altro pixel casuale posizionato sul display. Sarà lo stesso colore che hai scelto in precedenza.

4. Ora modifica le linee dei valori del colore in:
    
    ```python
r = randint (0, 255) g = randint (0, 255) b = randint (0, 255)
```

Ora il tuo programma selezionerà automaticamente un colore casuale.

5. Eseguilo nuovamente e dovresti vedere un altro pixel apparire in una posizione casuale con un colore casuale.

6. Eseguilo un paio di volte e dovresti vedere più della griglia riempire con pixel casuali.