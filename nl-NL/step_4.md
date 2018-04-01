## Afbeeldingen opmaken

Laten we de opmaak van de afbeelding op de poster verbeteren.

+ Op dit moment zijn er geen CSS-eigenschappen voor je `<img>` -tag, dus laten we er wat toevoegen!
    
    Voeg eerst de volgende code toe onder de CSS voor uw div:
    
        img {}
        
    
    ![screenshot](images/wanted-img-css.png)

+ We kunnen nu CSS-eigenschappen voor afbeeldingen toevoegen tussen de `` accolades.
    
    Voeg deze code bijvoorbeeld toe tussen de accolades om de breedte van de afbeelding in te stellen:
    
        breedte: 100 px;
        
    
    Je zult zien dat de grootte van de afbeelding verandert, zodat de breedte 100 pixels is.
    
    ![screenshot](images/wanted-img-width.png)

+ Je kunt ook een rand rond de afbeelding toevoegen met deze code:
    
        rand: 1px effen zwart;
        

+ Is het je opgevallen dat er niet veel ruimte is tussen het beeld en de rand?
    
    ![screenshot](images/wanted-img-border.png)
    
    U kunt dit oplossen door wat opvulling rond de afbeelding toe te voegen:
    
        opvulling: 10px;
        
    
    Opvulling is de ruimte tussen de inhoud (in dit geval een afbeelding) en de rand ervan.
    
    ![screenshot](images/wanted-img-padding.png)
    
    Wat denk je dat er zou gebeuren als je de opvulling veranderde in `50px`?