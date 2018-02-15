## Aggiungi un ciclo

Anziché lanciare di continuo il tuo programma, puoi aggiungere un ciclo in modo tale che i pixel si accendano di continuo.

1. Innanzitutto aggiungi un `import` all'inizio del file:
    
    ```python
from time import sleep
```

Lo userai nel programma per mettere in pausa tra l'accensione dei vari pixel.

2. Aggiungi nel codice una riga `while True:` in modo tale che le righe dove vengono generati i numeri casuali, `set_pixel` e `sleep` stiano tutte all'interno del ciclo:
    
    ```python
while True:
    x = randint(0, 7)
    y = randint(0, 7)
    r = randint(0, 255)
    g = randint(0, 255)
    b = randint(0, 255)
    sense.set_pixel(x, y, r, g, b)
    sleep(0.1)
```

3. Eseguendo il codice dovresti vedere in azione uno scintillio casuale!

4. Prova a cambiare il tempo di sonno per renderlo ancora più corto.