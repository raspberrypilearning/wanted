## Başlıkları şekillendirme

`<h1>` başlığının şeklini geliştirelim.

+ Resminizin CSS'inin altına aşağıdaki kodu ekleyin:
    
        h1 {
        
        }
        
    
    Burası ana `<h1>` başlığınız için CSS özelliklerini ekleyeceğiniz yerdir.

+ `<h1>` başlıklarınızın yazı tipini değiştirmek için, kıvrımlı parantezler arasına aşağıdaki kodu ekleyin:
    
        font-family: Impact;
        

+ Başlığın boyutunu da değiştirebilirsiniz:
    
        font-size: 50pt;
        

+ `<h1>` başlığı ile başlığın etrafındakilerle arasında büyük bir boşluk olduğunu fark ettin mi?
    
    ![ekran görüntüsü](images/wanted-h1-margin.png)
    
    Bunun nedeni, başlığın etrafında marjin (kenar boşluğu) olması. Kenar boşluğu, eleman (bu durumda bir başlık) ile etrafındaki diğer şeyler arasındaki boşluktur.
    
    Kenar boşluğunu bu kodla daha küçük hale getirebilirsiniz:
    
        margin: 10px;
        
    
    ![ekran görüntüsü](images/wanted-h1-margin-small.png)

+ Başlığınızın altını da çizebilirsiniz:
    
        text-decoration: underline;