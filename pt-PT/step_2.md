## Estilizar o teu cartaz

Vamos começar por editar o código CSS para o cartaz.

+ Abre este trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    O projeto deve-se parecer com isto:
    
    ![screenshot](images/wanted-starter.png)

+ Clica na aba "style.css". Vais notar que já existem propriedades CSS para `div` contendo as diferentes partes do cartaz.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Vamos começar por alterar o alinhamento de texto com a propriedade `text-align`:
    
        text-align: center;
        
    
    O que acontece quando mudas a palavra `center` para `left` ou `right`?

+ E quanto á propiedade `border`?
    
        border: 2px solid black;
        
    
    `2px` in the code above means 2 pixels. What happens when you change `2px solid black` to `4px dotted red`?

+ Change the `width` of the poster to `400px`. What happens to the poster?

+ Let's add some CSS to set the background colour of the poster. Go to the end of line 5 of your code and press return, so that you have a new blank line.
    
    ![screenshot](images/wanted-newline.png)
    
    Type the following code on your new blank line:
    
        background: yellow;
        
    
    Make sure that you type in the code *exactly* as it is above. You should notice that the background of the `<div>` is now yellow.
    
    ![screenshot](images/wanted-background.png)