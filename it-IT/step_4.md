## Utilizzare il modulo random

Finora sei stato tu a scegliere i numeri, ma puoi fare in modo che sia il computer a sceglierli.

1. Aggiungi un'altra riga `import` all'inizio del programma, appena sotto alla riga `import SenseHat`:
    
    ```python
from random import randint
```

2. Ora modifica le righe `x =` e `y =` in modo da selezionare automaticamente una posizione:
    
    ```python
x = randint(0, 7) 
y = randint(0, 7)
```

3. Esegui nuovamente il programma. Dovresti vedere un altro pixel accendersi a caso sul display. Sarà dello stesso colore che hai scelto in precedenza.

4. Ora modifica le righe relative ai valori del colore:
    
    ```python
r = randint(0, 255)
g = randint(0, 255)
b = randint (0, 255)
```

In questo modo, il programma selezionerà automaticamente un colore a caso.

5. Esegui di nuovo il tuo codice. Dovresti vedere un altro pixel apparire in una posizione a caso e con un colore a caso.

6. Esegui il codice ancora un paio di volte. Vedrai la griglia riempirsi di pixel disposti a caso e con colori a caso.