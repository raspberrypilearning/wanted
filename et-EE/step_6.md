## Laadipealkirjad

Parandame `<h1>` pealkirja stiili.

+ Lisa oma pildi CSS-i alla järgmine kood:
    
        h1 {
        
        }
        
    
    Siin lisad oma `<h1>` põhipealkirjale CSS-omadused.

+ Oma `<h1>` pealkirjade fondi muutmiseks lisa looksulgudes järgmine kood:
    
        font-family: Impact;
        

+ Saad muuta ka pealkirja suurust:
    
        font-size: 50pt;
        

+ Kas oled märganud, et `<h1>` pealkirja ja seda ümbritseva vahel on palju ruumi?
    
    ![kuvatõmmis](images/wanted-h1-margin.png)
    
    Seda seetõttu, et pealkirja ümber on veeris. Veeris on elemendi (antud juhul pealkirja) ja seda ümbritseva vaheline ala.
    
    Selle koodiga saad veerist vähendada:
    
        margin: 10px;
        
    
    ![kuvatõmmis](images/wanted-h1-margin-small.png)

+ Võid oma pealkirja ka alla joonida:
    
        text-decoration: underline;