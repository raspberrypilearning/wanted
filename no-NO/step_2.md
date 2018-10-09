## Styling din plakat

La oss starte med å redigere CSS-koden for plakaten.

+ Åpne denne pyntet: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Prosjektet skal se slik ut:
    
    ![skjermbilde](images/wanted-starter.png)

+ Klikk på kategorien "style.css". Du vil merke at det allerede finnes CSS egenskaper for `div` inneholder de forskjellige delene av plakaten.
    
        div {
            text-align: center;
            overløp: skjult;
            border: 2px solid svart;
            bredde: 300px;
        }   
        

+ La oss begynne med å endre `tekstjustering` egenskapen:
    
        tekst-align: center;
        
    
    Hva skjer når du endrer ordet `senter` til `igjen` eller `høyre`?

+ Hva med `grensen` eiendommen?
    
        border: 2px solid black;
        
    
    `2px` i koden ovenfor betyr 2 piksler. Hva skjer når du bytter `2px solid svart` til `4px prikket rødt`?

+ Endre `bredden` på plakaten til `400px`. Hva skjer med plakaten?

+ La oss legge til noe CSS for å angi bakgrunnsfargen på plakaten. Gå til slutten av linje 5 i koden din og trykk på retur, slik at du har en ny blank linje.
    
    ![skjermbilde](images/wanted-newline.png)
    
    Skriv inn følgende kode på den nye blanke linjen:
    
        bakgrunn: gul;
        
    
    Pass på at du skriver inn koden *nøyaktig* som den er over. Du bør legge merke til at bakgrunnen til `<div>` er nå gul.
    
    ![skjermbilde](images/wanted-background.png)