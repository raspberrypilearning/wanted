## Styling headings

Miglioriamo lo stile dell'intestazione `<h1>`.

+ Aggiungi questo codice sotto la regola CSS dell'immagine:
    
        h1 { 
        
        }
        
    
    Qui dentro aggiungeremo le proprietà CSS per l'intestazione `<h1>`.

+ Aggiungi il codice qui sotto per cambiare il font dell'intestazione `<h1>`:
    
        font-family: Impact;
        

+ Puoi anche cambiare la dimensione l'intestazione:
    
        font-size: 50pt;
        

+ Hai notato che c'è molto spazio tra l'intestazione `<h1>` e quello che le sta intorno?
    
    ![screenshot](images/wanted-h1-margin.png)
    
    This is because there's a margin around the heading. A margin is the space between the element (in this case a heading) and the other stuff around it.
    
    You can make the margin smaller with this code:
    
        margin: 10px;
        
    
    ![screenshot](images/wanted-h1-margin-small.png)

+ You can also underline your heading:
    
        text-decoration: underline;