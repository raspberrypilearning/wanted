## Judul gaya

Mari tingkatkan gaya tajuk `<h1>`.

+ Tambahkan kode berikut di bawah CSS gambar Anda:
    
        h1 {
        
        }
        
    
    Di sinilah kamu akan menambahkan properti CSS untuk judul utama `<h1>`.

+ Untuk mengubah font judul `<h1>`, tambahkan kode berikut di antara tanda kurung kurawal:
    
        font-family: Impact;
        

+ Kamu juga dapat mengubah ukuran judul:
    
        font-size: 50pt;
        

+ Apakah kamu memperhatikan bahwa ada jarak yang besar antara Judul `<h1>` dan bagian-bagian di sekitarnya?
    
    ![tangkapan layar](images/wanted-h1-margin.png)
    
    Ini karena ada margin di sekitar judul. Margin adalah ruang antara elemen (dalam hal ini judul) dan hal-hal lain di sekitarnya.
    
    Kamu dapat mengecilkan margin dengan kode ini:
    
        margin: 10px;
        
    
    ![tangkapan layar](images/wanted-h1-margin-small.png)

+ Kamu juga dapat memberi garis bawah untuk judul kamu:
    
        text-decoration: underline;