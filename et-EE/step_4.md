## Piltide kujundamine

Täiustame plakatil oleva pildi stiili.

+ Praegu ei ole sinu `&lt;img&gt;` sildi jaoks ühtegi CSS-omadust, nii et lisame mõned!
    
    Esmalt lisa oma div-i CSS-i alla järgmine kood:
    
        img {
        
        }
        
    
    ![kuvatõmmis](images/wanted-img-css.png)

+ Nüüd võime piltidele lisada ``looksulgudes CSS-omadused.
    
    Näiteks lisage see kood pildi laiuse määramiseks vahekaartide vahel:
    
        laius: 100px;
        
    
    Näete, et pildi suurus muutub, nii et selle laius on 100 pikslit.
    
    ![ekraanipilt](images/wanted-img-width.png)

+ Selle koodiga saate lisada pildile ka piiri:
    
        piiri: 1px tahke must;
        

+ Kas olete märganud, et pildi ja piiri vahel pole palju ruumi?
    
    ![ekraanipilt](images/wanted-img-border.png)
    
    Seda saab parandada, lisades pilti pildi ümber:
    
        padding: 10px;
        
    
    Padding on ruum sisu (antud juhul pilt) ja selle piiri vahel.
    
    ![ekraanipilt](images/wanted-img-padding.png)
    
    Mis te arvate, kui vahetate postituse `pikslit`?