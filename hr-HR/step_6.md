## Naslovi za oblikovanje

Poboljšamo stil zaglavlja `&lt;h1&gt;`.

+ Dodajte sljedeći kôd ispod CSS-a svoje slike:
    
        h1 {
        
        }
        
    
    Ovdje ćete dodati svojstva CSS-a za svoj glavni `&lt;h1&gt;` naslov.

+ Da biste promijenili font za `&lt;h1&gt;` naslove, dodajte sljedeći kôd između vitičastih zagrada:
    
        font-family: Impact;
        

+ Također možete promijeniti veličinu naslova:
    
        font-size: 50pt;
        

+ Jeste li primijetili da postoji veliki prostor između naslova `&lt;h1&gt;` i stvari oko njega?
    
    ![screenshot](images/wanted-h1-margin.png)
    
    To je zato što postoji granica oko naslova. Margina je prostor između elementa (u ovom slučaju naslova) i ostalih stvari oko njega.
    
    S tim kodom možete smanjiti marginu:
    
        margin: 10px;
        
    
    ![screenshot](images/wanted-h1-margin-small.png)

+ You can also underline your heading:
    
        text-decoration: underline;