## Stilizovanje slika

Poboljšajmo stil slike u plakatu.

+ Trenutno nema nijednog CSS svojstva za oznaku `<img>`. Dodajmo neke!
    
    Za početak, dodajmo sljedeći kôd ispod CSS-a za tvoj div:
    
        img {
        
        }
        
    
    ![screenshot](images/wanted-img-css.png)

+ Sada možemo da dodamo CSS svojstva za slike između vitičastih zagrada { }.
    
    Na primjer, između vitičastih zagrada dodaj sljedeći kôd da odrediš širinu slike:
    
        width: 100px;
        
    
    Vidjećeš da se veličina slike promijenila. Sada je njena širina 100 piksela.
    
    ![screenshot](images/wanted-img-width.png)

+ You can also add a border around the image with this code:
    
        border: 1px solid black;
        

+ Have you noticed that there's not much space between the image and the border?
    
    ![screenshot](images/wanted-img-border.png)
    
    You can fix this by adding some padding around the image:
    
        padding: 10px;
        
    
    Padding is the space between the content (in this case an image) and its border.
    
    ![screenshot](images/wanted-img-padding.png)
    
    What do you think would happen if you changed the padding to `50px`?