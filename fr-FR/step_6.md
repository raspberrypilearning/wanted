## Stylise ton titre

Améliorons le style du titre `<h1>`.

+ Ajoute le code suivant sous le CSS de ton image :
    
        h1 {
        
        }
        
    
    C’est là que tu vas ajouter des propriétés CSS pour ton titre principal `<h1>`.

+ Pour changer la police de tes titres `<h1>`, ajoute le code suivant entre les accolades :
    
        font-family: Impact;
        

+ Tu peux aussi modifier la taille de ton titre :
    
        font-size: 50pt;
        

+ As-tu remarqué qu'il y a un grand espace entre le titre `<h1>` et les éléments qui l'entourent ?
    
    ![capture d'écran](images/wanted-h1-margin.png)
    
    C'est parce qu'il y a une marge autour du titre. Une marge est l'espace entre l'élément (dans ce cas un titre) et les autres éléments qui l'entourent.
    
    Tu peux réduire la marge avec ce code :
    
        margin: 10px;
        
    
    ![capture d'écran](images/wanted-h1-margin-small.png)

+ Tu peux également souligner ton titre :
    
        text-decoration: underline;