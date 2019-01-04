## Laadipealkirjad

Parandame `&lt;h1&gt;` pealkirja stiili.

+ Lisa oma pildi CSS-i alla järgmine kood:
    
        h1 {
        
        }
        
    
    Siin lisad oma `&lt;h1&gt;` põhipealkirjale CSS-omadused.

+ Oma `&lt;h1&gt;` pealkirjade fondi muutmiseks lisa looksulgudes järgmine kood:
    
        font-family: Impact;
        

+ Saad muuta ka pealkirja suurust:
    
        font-size: 50pt;
        

+ Kas oled märganud, et `&lt;h1&gt;` pealkirja ja seda ümbritseva vahel on palju ruumi?
    
    ![kuvatõmmis](images/wanted-h1-margin.png)
    
    Seda seetõttu, et pealkirja ümber on varu. Märgistus on elemendi (antud juhul rubriigi) ja selle ümbruses asuvate ruumide vaheline kaugus.
    
    Selle koodiga saab marginaali vähendada:
    
        marginaal: 10px;
        
    
    ![ekraanipilt](images/wanted-h1-margin-small.png)

+ Võite rõhutada ka pealkirja:
    
        tekstikujundus: rõhutage;