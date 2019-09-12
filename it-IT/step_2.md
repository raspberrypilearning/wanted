## Personalizza il tuo poster

Iniziamo modificando il codice CSS del poster.

+ Apri questo trinket: <a target="_blank" href="https://trinket.io/html/7c6760e4d1">trinket.io/html/7c6760e4d1</a>.
    
    Il progetto dovrebbe assomigliare a questo:
    
    ![schermata](images/wanted-starter.png)

+ Fai clic sulla scheda "style.css". Noterai che esistono già delle proprietà CSS per il `div` che contiene le diverse parti del poster.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Inizia modificando la proprietà `text-align`:
    
        text-align: center;
        
    
    Che succede quando cambi la parola `center` in `left` o `right`?

+ Proviamo con la proprietà `border`?
    
        border: 2px solid black;
        
    
    `2px` nel codice qui sopra significa 2 pixel. Cosa succede cambiando `2px solid black` in `4px dotted red`?

+ Porta la `width` del poster a `400px`. Cosa succede al poster?

+ Aggiungiamo del CSS per impostare il colore dello sfondo del poster. Vai alla fine della riga 5 del codice e premi Invio, così da creare una nuova riga vuota.
    
    ![schermata](images/wanted-newline.png)
    
    Copia il codice qui sotto nella nuova riga:
    
        background: yellow;
        
    
    Assicurati di scrivere il codice *esattamente* come riportato qui sopra. Dovresti notare che lo sfondo del `<div>` è diventato giallo.
    
    ![schermata](images/wanted-background.png)