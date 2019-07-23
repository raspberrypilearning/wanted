## Görüntüleri şekillendirme

Posterdeki görüntünün tarzını geliştirelim.

+ Şu anda `<img>` etiketiniz için herhangi bir CSS özelliği yok, o yüzden biraz ekleyelim!
    
    Öncelikle, div'iniz için CSS'in altına aşağıdaki kodu ekleyin:
    
        img {
        
        }
        
    
    ![ekran görüntüsü](images/wanted-img-css.png)

+ Şimdi kıvrımlı parantezin içine resmin CSS özelliklerini ekleyebiliriz.
    
    Örneğin, görüntünün genişliğini ayarlamak için bu kodu kıvrımlı parantezlerin arasına ekleyin:
    
        width: 100px;
        
    
    Görüntünün boyutunun değiştiğini göreceksiniz, böylece genişliği 100 piksel olacaktır.
    
    ![ekran görüntüsü](images/wanted-img-width.png)

+ Bu kodla resmin etrafına kenarlık da ekleyebilirsiniz:
    
        border: 1px solid black;
        

+ Görüntü ve kenarlık arasında pek fazla boşluk olmadığını farkettiniz mi?
    
    ![ekran görüntüsü](images/wanted-img-border.png)
    
    Resmin çevresine biraz dolgu ekleyerek bunu düzeltebilirsiniz:
    
        padding: 10px;
        
    
    Dolgu, içerik (bu durumda bir resim) ile kenarlığı arasındaki boşluktur.
    
    ![ekran görüntüsü](images/wanted-img-padding.png)
    
    Dolguyu `50px` ile değiştirirseniz ne olacağını düşünüyorsunuz?