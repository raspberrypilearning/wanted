## Piltide kujundamine

Täiustame plakatil oleva pildi stiili.

+ Praegu ei ole sinu `&lt;img&gt;` sildi jaoks ühtegi CSS-omadust, nii et lisame mõned!
    
    Esmalt lisa oma div-i CSS-i alla järgmine kood:
    
        img {
        
        }
        
    
    ![kuvatõmmis](images/wanted-img-css.png)

+ We can now add CSS properties for images between the curly brackets.
    
    Lisa näiteks see kood looksulgude vahel pildi laiuse määramiseks:
    
        width: 100px;
        
    
    Näed, et pildi suurus muutub, selle laius on nüüd 100 pikslit.
    
    ![kuvatõmmis](images/wanted-img-width.png)

+ Selle koodiga saad lisada pildile ka äärise:
    
        border: 1px solid black;
        

+ Kas oled märganud, et pildi ja äärise vahel pole palju ruumi?
    
    ![kuvatõmmis](images/wanted-img-border.png)
    
    Saad seda parandada, lisades pildi ümber natuke täidist:
    
        padding: 10px;
        
    
    Täidis on ruum sisu (antud juhul pilt) ja selle äärise vahel.
    
    ![kuvatõmmis](images/wanted-img-padding.png)
    
    Mis sinu meelest juhtub, kui muudad täidise suurust `50px-ni`?