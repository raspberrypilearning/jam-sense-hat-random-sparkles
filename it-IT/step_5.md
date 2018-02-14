## Aggiungi un ciclo

Piuttosto che dover continuare a eseguire il tuo programma, puoi aggiungere un ciclo in modo che continui a funzionare.

1. Innanzitutto, aggiungi un `import` all'inizio del tuo file:
    
    ```python
dal momento dell'importazione, dormi
```

Lo userai per mettere in pausa il programma tra i pixel.

2. Aggiungi un `mentre True:` al codice in modo che le righe casuali, `set_pixel` e `sonno` sono tutti all'interno del ciclo:
    
    ```python
while True: x = randint (0, 7) y = randint (0, 7) r = randint (0, 255) g = randint (0, 255) b = randint (0, 255) sense.set_pixel (x, y , r, g, b) sleep (0.1)
```

3. Esegui il codice e dovresti vedere scintille casuali in azione!

4. Prova a cambiare il tempo di sonno per renderlo ancora più corto.