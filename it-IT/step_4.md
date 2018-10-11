## Modificare l'aspetto delle immagini

Miglioriamo l'aspetto dell'immagine nel poster.

+ Al momento, non ci sono proprietà CSS per il tuo tag `<img>`, aggiungiamone un po'!
    
    Per prima cosa, aggiungi questo codice sotto il CSS relativo al tuo div:
    
        img {
        
        }
        
    
    ![screenshot](images/wanted-img-css.png)

+ Ora possiamo aggiungere delle proprietà CSS per le immagini tra le parentesi graffe.
    
    Ad esempio, aggiungi questo codice tra le graffe per impostare la larghezza dell'immagine:
    
        width: 100px;
        
    
    Vedrai che la dimensione dell'immagine cambierà, e la sua larghezza diventerà 100 pixel.
    
    ![screenshot](images/wanted-img-width.png)

+ Puoi anche aggiungere un bordo attorno all'immagine con questo codice:
    
        border: 1px solid black;
        

+ Have you noticed that there's not much space between the image and the border?
    
    ![screenshot](images/wanted-img-border.png)
    
    You can fix this by adding some padding around the image:
    
        padding: 10px;
        
    
    Padding is the space between the content (in this case an image) and its border.
    
    ![screenshot](images/wanted-img-padding.png)
    
    What do you think would happen if you changed the padding to `50px`?