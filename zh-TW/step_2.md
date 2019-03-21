## 造型你的海報

讓我們從編輯海報的CSS代碼開始。

+ 打開這個小飾品： <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>。
    
    該項目應如下所示：
    
    ![截圖](images/wanted-starter.png)

+ 單擊“style.css”選項卡。你會注意到 `div` 已經有了包含海報不同部分的CSS屬性。
    
        div {
            text-align：center;
            溢出：隱藏;
            邊框：2px純黑色;
            寬度：300px;
        }   
        

+ 讓我們從改變 `text-align` 屬性開始：
    
        text-align：center;
        
    
    將單詞 `center` 更改為 `左` 或 `右`什麼？

+ `邊境` 物業怎麼樣？
    
        邊框：2px純黑色;
        
    
    上面代碼中的`2px` 表示2個像素。當你改變 `2px實心黑色` 到 `4px點綴紅色`什麼？

+ 將海報的 `寬` 更改為 `400px`。海報怎麼了？

+ 讓我們添加一些CSS來設置海報的背景顏色。轉到代碼第5行的末尾並按回車鍵，以便有一個新的空白行。
    
    ![截圖](images/wanted-newline.png)
    
    在新的空行上鍵入以下代碼：
    
        背景：黃色;
        
    
    確保您在上面輸入的代碼 *正好為* 。您應該注意到 `<div>` 的背景現在是黃色的。
    
    ![截圖](images/wanted-background.png)