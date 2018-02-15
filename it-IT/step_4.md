## Uso del modulo random

Finora hai scelto tu i numeri, ma puoi fare in modo che sia il computer a sceglierli.

1. Aggiungi un'altra riga di `import` nella parte superiore del programma, subito sotto alla riga `import SenseHat`:
    
    ```python
from random import randint
```

2. Ora modifica le righe `x =` e `y =` in modo da selezionare automaticamente una posizione:
    
    ```python
x = randint(0, 7) 
y = randint(0, 7)
```

3. Esegui nuovamente il programma e dovresti vedere un altro pixel posizionato a caso sul display. Sarà dello stesso colore che hai scelto in precedenza.

4. Ora modifica le righe relative ai valori del colore:
    
    ```python
r = randint(0, 255)
g = randint(0, 255)
b = randint (0, 255)
```

Ora il programma selezionerà automaticamente un colore a caso.

5. Eseguilo nuovamente e dovresti vedere un altro pixel apparire in una posizione a caso e con un colore casuale.

6. Eseguilo un altro paio di volte e dovresti vedere la griglia riempirsi di pixel disposti a caso e con colori casuali.