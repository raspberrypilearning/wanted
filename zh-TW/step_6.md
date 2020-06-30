## 設定標題樣式

讓我們改進 `<h1>` 標題的風格。

+ 在圖片 CSS 的下方新增以下代碼：
    
        h1 {
        
        }
        
    
    這就是你將向`<h1>`主標題新增 CSS 屬性的地方。

+ 要更改 `<h1>` 標題的字型，在大括號之間新增以下代碼：
    
        font-family: Impact;
        

+ 您還可以更改標題的大小：
    
        font-size：50pt;
        

+ 你有沒有注意到 `<h1>` 標題和它周圍的東西之間有一個很大的空間？
    
    ![截圖](images/wanted-h1-margin.png)
    
    這是因為標題周圍有一個邊距。邊距指元素（在這裡是一個標題）與其周圍的其他內容之間的間距。
    
    你可以使用以下代碼來縮小邊距
    
        margin: 10px;
        
    
    ![截圖](images/wanted-h1-margin-small.png)

+ 你還可以為你的標題新增底線：
    
        text-decoration: underline;