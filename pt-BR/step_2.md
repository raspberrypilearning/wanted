## Estilizando seu pôster

Vamos começar editando o código CSS do pôster.

+ Abra este trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-letter</a>.
    
    O projeto deve ficar assim:
    
    ![screenshot](images/wanted-starter.png)

+ Clique na aba "style.css". Você notará que já existem propriedades CSS para o ` div ` contendo as diferentes partes do cartaz.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Vamos começar alterando a propriedade `text-align`:
    
        text-align: center;
        
    
    O que acontece quando você muda a palavra ` center` (centralizar) para ` left` (esquerda) ou ` rignt` (direita)?

+ Que tal mudar a propriedade `border`?
    
        border: 2px solid black;
        
    
    ` 2 px ` no código acima significa 2 pixels. O que acontece quando você altera o 2x preto sólido ` solid black 2px ` para 4x pontilhado vermelho` 4px dotted red `?

+ Altere a largura `width ` do poster para ` 400 px `. O que acontece com o ele?

+ Let's add some CSS to set the background colour of the poster. Go to the end of line 5 of your code and press return, so that you have a new blank line.
    
    ![screenshot](images/wanted-newline.png)
    
    Type the following code on your new blank line:
    
        background: yellow;
        
    
    Make sure that you type in the code *exactly* as it is above. You should notice that the background of the `<div>` is now yellow.
    
    ![screenshot](images/wanted-background.png)