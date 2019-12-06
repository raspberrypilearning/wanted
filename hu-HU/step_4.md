## Stílusos képek

Javítsuk a kép stílusát a poszterben.

+ Jelenleg nincs `<img>` tulajdonság a ` <img> ` címkéhez, szóval adjunk hozzá néhányat!
    
    Először adja hozzá a következő kódot a divs CSS alá:
    
        img {
        
        }
        
    
    ![screenshot](images/wanted-img-css.png)

+ Most hozzáadhatunk CSS tulajdonságokat a képekhez a göndör zárójelben.
    
    Például adja hozzá ezt a kódot a göndör zárójelek közé a kép szélességének beállításához:
    
        szélesség: 100 képpont;
        
    
    Látni fogja, hogy a kép mérete megváltozik, így szélessége 100 pixel.
    
    ![screenshot](images/wanted-img-width.png)

+ A kép körül szegélyt is felvehet a következő kóddal:
    
        szegély: 1 képpont szilárd fekete;
        

+ Észrevetted, hogy nincs sok hely a kép és a keret között?
    
    ![screenshot](images/wanted-img-border.png)
    
    Javíthatja ezt a kép körül néhány párnázattal:
    
        párnázat: 10 képpont;
        
    
    A padding az a tartalom (ebben az esetben egy kép) és a szegély közötti tér.
    
    ![screenshot](images/wanted-img-padding.png)
    
    Ön szerint mi történne, ha a párnát `50px`?