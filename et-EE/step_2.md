## Enda plakati kujundamine

Alustame plakati CSS-koodi redigeerimisest.

+ Ava see trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Projekt peaks välja nägema selline:
    
    ![kuvatõmmis](images/wanted-starter.png)

+ Klõpsa vahekaardil "style.css". Märkad, et CSS-omadused `div` jaoks on juba seal, sisaldades plakati eri osi.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Alustame `text-align` omaduse muutmisest:
    
        text-align: center;
        
    
    Mis juhtub, kui muudad sõna `keskpunkt` kuni `vasakule` või `paremat`?

+ Kuidas umbes `piiri` vara?
    
        piiri: 2px tahke must;
        
    
    Eespool olevas koodis `2px` tähendab 2 pikslit. Mis juhtub siis, kui vahetate `2px tahke musta` kuni `4px punktiirjoonega punast`?

+ Muuda plakati `laius` kuni `400 pikslit`. Mis juhtub plakatiga?

+ Lisame plakati taustavärvi mõne CSS-i. Mine oma koodi rea 5 lõppu ja vajutage tagasisaatmist, nii et teil on uus tühi rida.
    
    ![ekraanipilt](images/wanted-newline.png)
    
    Sisestage järgmine uus tühi rida:
    
        taust: kollane;
        
    
    Veenduge, et sisestasite koodi *täpselt* nagu eespool. Te peaksite tähele panema, et `<div>` taust on nüüd kollane.
    
    ![ekraanipilt](images/wanted-background.png)