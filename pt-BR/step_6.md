## Estilizando Cabeçalhos

Vamos melhorar o estilo do cabeçalho `<h1>`.

+ Adicione o seguinte código abaixo do CSS da sua imagem:
    
        h1 {
        
        }
        
    
    É aqui que você adicionará as propriedades CSS ao seu cabeçalho principal `<h1>`.

+ Para alterar a fonte dos seus cabeçalhos `<h1>`, adicione o seguinte código entre as chaves:
    
        font-family: Impact;
        

+ Você também pode alterar o tamanho do cabeçalho:
    
        font-size: 50pt;
        

+ Você notou que há um grande espaço entre o cabeçalho `<h1>` e as coisas ao redor dele?
    
    ![captura de tela](images/wanted-img-padding.png)
    
    Isso ocorre porque há uma margem ao redor do cabeçalho. Uma margem é o espaço entre o elemento (neste caso, um cabeçalho) e as outras coisas ao redor dele.
    
    Você pode diminuir a margem com este código:
    
        margin: 10px;
        
    
    ![captura de tela](images/wanted-img-padding.png)

+ Você também pode sublinhar seu título:
    
        text-decoration: underline;