## Usare set_pixel

Per prima cosa, pensa a dei numeri a caso e utilizza la funzione `set_pixel` per accendere un colore a caso, in una posizione a caso, sul display del Sense HAT.

1. Se stai usando un Raspberry Pi, apri Python 3 e crea un nuovo file. Se stai utilizzando l'emulatore web, elimina il codice di esempio prima di cominciare.

2. Prima di tutto, nel nuovo file, importa il modulo Sense HAT.
    
    Se stai usando un Sense HAT vero e proprio o l'emulatore Trinket, inserisci la seguente riga per importare il modulo:
    
    ```python
    from sense_hat import SenseHat
    ```

    Se stai usando l'emulatore desktop, inserisci la seguente riga per importare il modulo:

    ```python
    from sense_emu import SenseHat
    ```

    Il resto del codice sarà identico per tutte le versioni.

3. Adesso connettiti al Sense HAT aggiungendo questa riga:
    
    ```python
    sense = SenseHat()
    ```

4. Pensa a un numero a caso compreso tra 0 e 7, e assegnalo alla variabile `x`, ad esempio:
    
    ```python
    x = 4
    ```

5. Pensa ad un altro numero compreso tra 0 e 7, e assegnalo a `y`:
    
    ```python
    y = 5
    ```

6. Pensa a tre numeri a caso compresi tra 0 e 255, e assegnali a `r`, `g`, e `b`:
    
    ```python
    r = 19
    g = 180 
    b = 230
    ```

7. Ora usa la funzione `set_pixel` per posizionare il colore sul display:
    
    ```python
    sense.set_pixel(x, y, r, g, b)
    ```

8. Esegui il codice premendo **F5** (o il pulsante **Run**, se stai utilizzando Trinket). Un pixel dovrebbe accendersi.

9. Adesso scegli altri numeri a caso - tutti diversi dai precedenti - ed esegui di nuovo il programma. Sul display dovrebbe apparire un secondo pixel!
