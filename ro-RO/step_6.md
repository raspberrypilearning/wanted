## Stilizarea titlurilor

Să imbunătățim stilul pentru titlul pe care îl vom marca cu heading-ul `<h1>`.

+ Adaugă următorul cod sub CSS-ul imaginii tale:
    
        h1 {
        
        }
        
    
    Aici vei adăuga proprietăți CSS pentru titlul`<h1>`.

+ Pentru a îi schimba fontul adăugă între acolade:
    
        font-family: Impact;
        

+ Poți să schimbi, de asemenea, si dimensiunea textului din titlu:
    
        font-size: 50pt;
        

+ Ai observat că există un spațiu mare între titlul `<h1>` și celelalte elemente de pe afiș?
    
    ![captură de ecran](images/wanted-h1-margin.png)
    
    Acest lucru se datorează faptului că există o margine în jurul acestuia. O margine este spațiul dintre element (în acest caz titlul) și celelalte din jurul său.
    
    Poți reduce marginea astfel:
    
        margin: 10px;
        
    
    ![captură de ecran](images/wanted-h1-margin-small.png)

+ De asemenea, poți și sublinia textul din titlu:
    
        text-decoration: underline;