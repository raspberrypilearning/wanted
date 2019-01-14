## Şekillendirme görüntüleri

Posterdeki görüntünün tarzını geliştirelim.

+ Şu anda, `<img>` etiketiniz için herhangi bir CSS özelliği yok, o yüzden biraz ekleyelim!
    
    Öncelikle, div'iniz için CSS'in altına aşağıdaki kodu ekleyin:
    
        img {
        
        }
        
    
    ![ekran görüntüsü](images/wanted-img-css.png)

+ Kıvrımlı parantezler arasına görüntüler için şimdi CSS özelliklerini ekleyebiliriz.
    
    Örneğin, görüntünün genişliğini ayarlamak için bu kodu küme parantezleri arasına ekleyin:
    
        genişlik: 100px;
        
    
    Görüntünün boyutunun değiştiğini göreceksiniz, böylece genişliği 100 piksel olacaktır.
    
    ![ekran görüntüsü](images/wanted-img-width.png)

+ Bu kodla görüntünün etrafına kenarlık da ekleyebilirsiniz:
    
        sınır: 1px katı siyah;
        

+ Görüntü ve kenarlık arasında fazla boşluk olmadığını farkettiniz mi?
    
    ![ekran görüntüsü](images/wanted-img-border.png)
    
    Resmin çevresine biraz dolgu ekleyerek bunu düzeltebilirsiniz:
    
        dolgu maddesi: 10px;
        
    
    Dolgu, içerik (bu durumda bir görüntü) ile kenarlığı arasındaki boşluktur.
    
    ![ekran görüntüsü](images/wanted-img-padding.png)
    
    Dolgu `50px`değiştirirseniz ne olacağını düşünüyorsunuz?