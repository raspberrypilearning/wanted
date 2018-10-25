## Plakati kujundamine

Alustame postiindeksi CSS-koodi muutmisega.

+ Avage see nipsu: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web- soovitud</a>.
    
    Projekt peaks olema selline:
    
    ![ekraanipilt](images/wanted-starter.png)

+ Klõpsake vahekaardil "style.css". Saate märkida, et `sektsioon` sisaldab plakati eri osi, on juba CSS-i omadused.
    
        div {
            text-align: center;
            ülevool: peidetud;
            piiri: 2px tahke must;
            laius: 300px;
        }   
        

+ Alustame muutmaks `teksti-joondus` vara:
    
        teksti-joondus: keskus;
        
    
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