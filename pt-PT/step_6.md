## Estilizar cabeçalhos

Vamos melhorar o estilo do cabeçalho `<h1>`.

+ Adiciona o seguinte código abaixo do CSS da tua imagem:
    
        h1 {
        
        }
        
    
    É aqui que vais adicionar propriedades CSS para o teu cabeçalho principal `<h1>`.

+ Para alterar a fonte dos teus cabeçalhos `<h1>` adiciona o seguinte código entre as chavetas:
    
        font-family: Impact;
        

+ You can also change the size of the heading:
    
        font-size: 50pt;
        

+ Have you noticed that there's a big space between the `<h1>` heading and the stuff around it?
    
    ![screenshot](images/wanted-h1-margin.png)
    
    This is because there's a margin around the heading. A margin is the space between the element (in this case a heading) and the other stuff around it.
    
    You can make the margin smaller with this code:
    
        margin: 10px;
        
    
    ![screenshot](images/wanted-h1-margin-small.png)

+ You can also underline your heading:
    
        text-decoration: underline;