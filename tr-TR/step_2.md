## Posterinizi şekillendirin

Posterin CSS kodunu düzenleyerek başlayalım.

+ Şu trinketi açın: <a target="_blank" href="https://trinket.io/html/5b5d707ef5">jumpto.cc/web-wanted</a>.
    
    Proje şöyle görünmeli:
    
    ![ekran görüntüsü](images/wanted-starter.png)

+ "Style.css" sekmesine tıklayın. Posterin farklı bölümlerini içeren `div` için zaten CSS özelliklerinin olduğunu fark edeceksiniz.

    ```    
    div {
        text-align: center;
        overflow: hidden;
        border: 2px solid black;
        width: 300px;
    }
    ```  
        

+ `text-align` özelliğini değiştirerek başlayalım:
        
    ```
    text-align: center;
    ```

    
    `center` kelimesini `left` veya `right` kelimesiyle değiştirirseniz ne olur?

+ `border` özelliğine ne dersiniz?
    
    ```
    border: 2px solid black;
    ```    
    
    Yukarıdaki kodda `2px` 2 piksel anlamına gelir. `2px solid black` yazısını `4px dotted red` ile değiştirirseniz ne olur?

+ Posterin `width` değerini `400px` ile değiştirin. Postere ne olacak?

+ Posterin arka plan rengini ayarlamak için biraz CSS ekleyelim. Kodunuzun 5. satırının sonuna gidin ve return tuşuna basın, böylece yeni bir boş satırınız olur.
    
    ![ekran görüntüsü](images/wanted-newline.png)
    
    Yeni boş satırınıza aşağıdaki kodu yazın:
    
    ```
    background: yellow;
    ```    
    
    Kodu *tam olarak yukarıdaki gibi* yazdığınızdan emin olun. `<div>`'in arka planının artık sarı olduğunu fark etmelisiniz.
    
    ![ekran görüntüsü](images/wanted-background.png)