## Gambar Styling

Mari tingkatkan gaya gambar di poster.

+ Saat ini, tidak ada properti CSS untuk tag `<img>` , jadi mari tambahkan beberapa!
    
    Pertama, tambahkan kode berikut di bawah CSS untuk div kamu:
    
        img {
        
        }
        
    
    ![tangkapan layar](images/wanted-img-css.png)

+ Sekarang kita bisa menambahkan properti CSS pada gambar di antara tanda kurung.
    
    Contohnya, tambahkan kode ini di antara kurung kurawal untuk mengatur lebar gambar:
    
        width: 100px;
        
    
    Kamu akan melihat bahwa ukuran gambar berubah, sehingga lebarnya 100 piksel.
    
    ![tangkapan layar](images/wanted-img-width.png)

+ Kamu juga dapat menambahkan garis batas di sekitar gambar dengan kode ini:
    
        border: 1px solid black;
        

+ Pernahkah kamu memperhatikan bahwa tidak ada banyak ruang antara gambar dan perbatasan?
    
    ![tangkapan layar](images/wanted-img-border.png)
    
    Kamu dapat memperbaikinya dengan menambahkan beberapa padding di sekitar gambar:
    
        padding: 10px;
        
    
    Padding adalah ruang antara konten (dalam hal ini gambar) dan garis batasnya.
    
    ![tangkapan layar](images/wanted-img-padding.png)
    
    Menurut kamu apa yang akan terjadi jika Anda mengubah padding menjadi `50px`?