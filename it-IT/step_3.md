## Utilizzando set_pixel

Per prima cosa, pensaimo a dei numeri a caso e usiamo la funzione `set_pixel` per accendere un colore a caso in una posizione casuale sul display del Sense HAT.

1. Se stai usando un Raspberry Pi, apri Python 3 e crea un nuovo file. Se stai utilizzando l'emulatore Web, elimina il codice di esempio prima di iniziare.

2. Prima di tutto, nel nuovo file, importa il modulo Sense HAT.
    
    Se stai usando un vero Sense HAT o l'emulatore Trinket, la linea per importare il modulo è:
    
    ```python
from sense_hat import SenseHat
```

Se stai usando l'emulatore desktop, la linea per importare il modulo è:

```python
from sense_emu import SenseHat
```

Il resto del codice sarà identico per tutte le versioni.

3. Quindi crea una connessione al Sense HAT aggiungendo questa riga:
    
    ```python
sense = SenseHat()
```

4. Adesso pensa a un numero a caso compreso tra 0 e 7, e assegnalo alla variabile `x`, ad esempio:
    
    ```python
x = 4
```

5. Pensa a un altro numero compreso tra 0 e 7, quindi assegnalo a `y`:
    
    ```python
y = 5
```

6. Pensa a tre numeri casuali compresi tra 0 e 255, quindi assegnali a `r`, `g`, e `b`:
    
    ```python
r = 19
g = 180 
b = 230
```

7. Ora usa la funzione `set_pixel` per posizionare il colore sul display:
    
    ```python
sense.set_pixel(x, y, r, g, b)
```

8. Ora esegui il codice premendo **F5** (o il pulsante **Esegui** se usi Trinket). Dovresti vedere un singolo pixel acceso.

9. Ora scegli altri numeri a caso - tutti diversi dai precedenti - ed esegui di nuovo il programma. Sul display dovrebbe apparire un secondo pixel!