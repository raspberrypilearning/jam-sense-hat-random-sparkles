## Utilizzando set_pixel

Per prima cosa, penseremo a numeri casuali e useremo il `set_pixel` funzione per posizionare un colore casuale in una posizione casuale sul display HAT Senso.

1. Se stai usando un Raspberry Pi, apri Python 3 e crea un nuovo file. Se stai utilizzando l'emulatore Web, elimina il codice di esempio prima di iniziare.

2. Nel nuovo file, iniziare importando il modulo Sense HAT.
    
    Se stai usando un vero HAT Sense o l'emulatore Trinket, la linea di importazione è:
    
    ```python
da sense_hat importa SenseHat
```

Se stai usando l'emulatore desktop, la linea di importazione è:

```python
da sense_emu import SenseHat
```

Il resto del codice sarà identico per tutte le versioni.

3. Quindi, crea una connessione al tuo HAT Sense aggiungendo:
    
    ```python
sense = SenseHat ()
```

4. Ora pensa a un numero casuale compreso tra 0 e 7 e assegnalo alla variabile `x`, ad esempio:
    
    ```python
x = 4
```

5. Pensa a un altro numero casuale tra 0 e 7, quindi assegnalo a `y`:
    
    ```python
y = 5
```

6. Pensa a tre numeri casuali compresi tra 0 e 255, quindi assegnali a `r`, `g`, e `b`:
    
    ```python
r = 19 g = 180 b = 230
```

7. Ora usa `set_pixel` funzione per posizionare il colore casuale nella posizione casuale sul display:
    
    ```python
sense.set_pixel (x, y, r, g, b)
```

8. Ora esegui il tuo codice premendo **F5** (o il pulsante **Esegui** in Trinket). Dovresti vedere un singolo pixel acceso.

9. Ora scegli alcuni nuovi numeri casuali - cambiali tutti - ed esegui di nuovo il programma. Un secondo pixel dovrebbe apparire sul display!