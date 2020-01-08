## ポスターのスタイリング

ポスターのCSSコードを編集することから始めましょう。

+ Trinketをひらく: jumpto.cc/web-wanted.
    
    プロジェクトはこのようになります。
    
    ![スクリーンショット](images/wanted-starter.png)

+ 「style.css」タブをクリックします。 ポスターのさまざまな部分を含むdivのCSSプロパティが既にあることに気づくでしょう。
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ text-align プロパティを変更することから始めましょう：
    
        text-align: center;
        
    
    単語 centerを、left左へまたはright右へ変更するとどうなりますか？ 

+ ボーダープロパティはどうですか？
    
        border: 2px solid black;
        
    
    `上のコードの2px` は2ピクセルを意味します。あなたが変更されたときに何が起こる `2ピクセルベタ黒` に `赤い点線4PX`？

+ 変更 `幅` にポスターのを `400ピクセル`。ポスターはどうなりますか？

+ ポスターの背景色を設定するCSSを追加しましょう。コードの5行目の最後に移動し、returnキーを押すと、新しい空白行が作成されます。
    
    ![スクリーンショット](images/wanted-newline.png)
    
    新しい空白行に次のコードを入力します。
    
        背景：黄色;
        
    
    上記のようにコード *正確に* 入力してください。 `<div>` 背景が黄色になります。
    
    ![スクリーンショット](images/wanted-background.png)