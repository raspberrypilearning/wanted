## Stilizovanje naslova

Poboljšajmo sada stil `<h1>` naslova.

+ Dodaj sljedeći kôd ispod CSS-a tvoje slike:
    
        h1 {
        
        }
        
    
    Tu ćeš dodati CSS svojstva za glavni `<h1>` naslov.

+ Za promjenu fonta `<h1>` naslova, između vitičastih zagrada dodaj sljedeći kôd:
    
        font-family: Impact;
        

+ Takođe možeš promijeniti veličinu naslova:
    
        font-size: 50pt;
        

+ Primjećuješ li da postoji veliki razmak između `<h1>` naslova i elemenata oko njega?
    
    ![screenshot](images/wanted-h1-margin.png)
    
    This is because there's a margin around the heading. A margin is the space between the element (in this case a heading) and the other stuff around it.
    
    You can make the margin smaller with this code:
    
        margin: 10px;
        
    
    ![screenshot](images/wanted-h1-margin-small.png)

+ You can also underline your heading:
    
        text-decoration: underline;