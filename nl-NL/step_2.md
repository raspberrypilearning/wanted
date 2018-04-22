## Je poster opmaken

Laten we beginnen met het bewerken van de CSS-code voor de poster.

+ Open deze trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Het project zou er als volgt uit moeten zien:
    
    ![screenshot](images/wanted-starter.png)

+ Klik op het tabblad "style.css". Je ziet dat er al CSS-eigenschappen zijn gemaakt voor de `div` waarin de verschillende onderdelen van de poster zitten.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Laten we beginnen met het wijzigen van de eigenschap `text-align`:
    
        text-align: center;
        
    
    Wat gebeurt er wanneer je het woord `center` wijzigt in `left` of `right`?

+ Wat dacht je van de `border` eigenschap?
    
        border: 2px solid black;
        
    
    `2px` in de bovenstaande code betekent 2 pixels. Wat gebeurt er wanneer je `2px solid black` in `4px dotted red` verandert?

+ Wijzig de `width` van de poster in `400 px`. Wat gebeurt er met de poster?

+ Laten we wat CSS toevoegen om de achtergrondkleur van de poster in te stellen. Ga naar het einde van regel 5 van je code en druk op Return, zodat je een nieuwe lege regel krijgt.
    
    ![screenshot](images/wanted-newline.png)
    
    Typ de volgende code op de nieuwe regel:
    
        background: yellow;
        
    
    Zorg ervoor dat je de code *precies* typt zoals hierboven staat. Je zou moeten zien dat de achtergrond van de `<div>` nu geel is.
    
    ![screenshot](images/wanted-background.png)