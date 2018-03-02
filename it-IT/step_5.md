## Aggiungi un ciclo

Invece di dover far partire il tuo programma manualmente di continuo, puoi aggiungere un ciclo in modo tale che i pixel si accendano continuamente da soli.

1. Innanzitutto aggiungi un `import` all'inizio del file:
    
    ```python
    from time import sleep
    ```

    Questa riga serve a far mettere il programma in pausa tra un'accensione e l'altra dei vari pixel.

2. Aggiungi al tuo codice la riga `while True:`, per far sì che le righe che generano i numeri a caso, la riga `set_pixel` e la riga `sleep` stiano tutte contenute all'interno del ciclo:
    
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

3. Eseguendo il codice dovresti veder partire scintillii a caso!

4. Prova a cambiare il tempo di nella funzione sleep, in modo da accorciare il tempo di pausa tra un'accensione e l'altra.
