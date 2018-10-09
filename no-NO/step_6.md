## Styling overskrifter

La oss forbedre stilen på `<h1>` overskriften.

+ Legg til følgende kode under bildet ditt:
    
        h1 {
        
        }
        
    
    Dette er hvor du legger til CSS-egenskaper for din hoved `<h1>` overskrift.

+ For å endre skrifttypen for `<h1>` overskriftene, legg til følgende kode mellom de krøllete parentesene:
    
        font-family: Impact;
        

+ Du kan også endre størrelsen på overskriften:
    
        skriftstørrelse: 50pt;
        

+ Har du lagt merke til at det er en stor plass mellom `<h1>` overskriften og ting rundt den?
    
    ![skjermbilde](images/wanted-h1-margin.png)
    
    Dette skyldes at det er en margin rundt overskriften. En margin er mellomrommet mellom elementet (i dette tilfellet en overskrift) og de andre tingene rundt den.
    
    Du kan gjøre marginen mindre med denne koden:
    
        margin: 10px;
        
    
    ![skjermbilde](images/wanted-h1-margin-small.png)

+ Du kan også understreke overskriften din:
    
        tekst-dekorasjon: understreke;