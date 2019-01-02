## Uređivanje slike

Poboljšamo stil slike u plakatu.

+ Trenutačno nema CSS svojstava za vašu `&lt;img&gt;` oznaku, pa dodajte nešto!
    
    Prvo dodajte sljedeći kôd ispod CSS-a za vaš div:
    
        img {
        
        }
        
    
    ![screenshot](images/wanted-img-css.png)

+ Sada možemo dodati CSS svojstva za slike između `` kovrčavih 'zagrada.
    
    Na primjer, dodajte ovaj kôd između kovrčavih zagrada da biste postavili širinu slike:
    
        width: 100px;
        
    
    Vidjet ćete da se veličina slike mijenja, tako da je širina 100 piksela.
    
    ![screenshot](images/wanted-img-width.png)

+ Ovom slikom možete dodati i obrub oko slike:
    
        border: 1px solid black;
        

+ Jeste li primijetili da nema mnogo prostora između slike i granice?
    
    ![screenshot](images/wanted-img-border.png)
    
    To možete popraviti dodavanjem neke obloge oko slike:
    
        padding: 10px;
        
    
    Padding je prostor između sadržaja (u ovom slučaju slike) i njegove granice.
    
    ![screenshot](images/wanted-img-padding.png)
    
    Što mislite da će se dogoditi ako promijenite padding na `50px`?