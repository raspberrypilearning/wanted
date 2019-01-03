## Enda plakati kujundamine

Alustame plakati CSS-koodi redigeerimisest.

+ Ava see trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Projekt peaks välja nägema selline:
    
    ![kuvatõmmis](images/wanted-starter.png)

+ Klõpsa vahekaardil "style.css". Märkad, et CSS-omadused `div` jaoks on juba seal olemas, sisaldades plakati eri osi.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Alustame omaduse `text-align` muutmisest:
    
        text-align: center;
        
    
    Mis juhtub, kui muudad sõna `center` sõnaks `left` või `right`?

+ Kuidas on lood omadusega `border`?
    
        border: 2px solid black;
        
    
    Ülaltoodud koodis tähendab `2px` 2 pikslit. Mis juhtub siis, kui asendad `2px solid black` `4px dotted red'iga`?

+ Muuda plakati `width` `400 piksliks`. Mis juhtub plakatiga?

+ Lisame natuke CSS-i, et panna paika plakati taustavärv. Mine oma koodi 5. rea lõppu ja vajuta naase, et sul tekiks uus tühi rida.
    
    ![kuvatõmmis](images/wanted-newline.png)
    
    Sisestage järgmine uus tühi rida:
    
        taust: kollane;
        
    
    Veenduge, et sisestasite koodi *täpselt* nagu eespool. Te peaksite tähele panema, et `<div>` taust on nüüd kollane.
    
    ![ekraanipilt](images/wanted-background.png)