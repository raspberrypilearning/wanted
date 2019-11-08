## Stylizacja nagłówków

Poprawmy styl nagłówka `<h1>`.

+ Dodaj następujący kod poniżej kodu CSS obrazu:
   ``` 
        h1 {
        
        }
   ```     
    
    Tutaj dodajesz właściwości CSS do głównego nagłówka `<h1>`.

+ Aby zmienić czcionkę nagłówków `<h1>`, dodaj następujący kod wewnątrz nawiasów klamrowych:
    ```
        font-family: Impact;
    ```   

+ Możesz również zmienić rozmiar nagłówka:
    ```
        font-size: 50pt;
    ```    

+ Czy zauważyliście, że jest duża przestrzeń pomiędzy pozycją `<h1>` i zawartością wokół niego?
    
    ![zrzut ekranu](images/wanted-h1-margin.png)
    
    Jest tak, ponieważ wokół nagłówka jest margines. Margines to przestrzeń między elementem (w tym przypadku nagłówkiem) a treścią wokół niego.
    
    Możesz zmniejszyć margines za pomocą tego kodu:
    ```
        margin: 10px;
    ```    
    
    ![zrzut ekranu](images/wanted-h1-margin-small.png)

+ Możesz także podkreślić swój nagłówek:
    ```
        text-decoration: underline;
    ```