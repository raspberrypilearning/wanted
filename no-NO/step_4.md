## Styling bilder

La oss forbedre stilen på bildet i plakaten.

+ For øyeblikket finnes det ingen CSS-egenskaper for `<img>` taggen din, så la oss legge til noen!
    
    Først legger du til følgende kode under CSS for div:
    
        img {
        
        }
        
    
    ![skjermbilde](images/wanted-img-css.png)

+ Vi kan nå legge til CSS egenskaper for bilder mellom `` krøllete parenteser.
    
    For eksempel, legg til denne koden mellom de krøllete parentesene for å angi bredden på bildet:
    
        bredde: 100px;
        
    
    Du ser at størrelsen på bildet endres, slik at bredden er 100 piksler.
    
    ![skjermbilde](images/wanted-img-width.png)

+ Du kan også legge til en kant rundt bildet med denne koden:
    
        grense: 1 px solid svart;
        

+ Har du lagt merke til at det ikke er mye plass mellom bildet og grensen?
    
    ![skjermbilde](images/wanted-img-border.png)
    
    Du kan fikse dette ved å legge til noe polstring rundt bildet:
    
        polstring: 10px;
        
    
    Padding er mellomrommet mellom innholdet (i dette tilfellet et bilde) og grensen.
    
    ![skjermbilde](images/wanted-img-padding.png)
    
    Hva tror du ville skje hvis du endret polstring til `50px`?