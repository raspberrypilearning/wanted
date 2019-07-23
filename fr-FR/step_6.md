## Styliser ton titre

Améliorons le style de la rubrique `<h1>`.

+ Ajoute le code suivant sous le CSS de ton image:
    
        h1 {
        
        }
        
    
    C’est là que tu vas ajouter des propriétés CSS pour ton en-tête principale `<h1>`.

+ Pour changer la police de tes en-têtes `<h1>`, ajoute le code suivant entre les accolades:
    
        font-family: Arial;
        

+ Tu peux aussi modifier la taille de l'image:
    
        font-size: 50pt;
        

+ As-tu remarqué qu'il y a un grand espace entre l'en-tête `<h1>` et les éléments qui l'entourent?
    
    ![capture d'écran](images/wanted-h1-margin.png)
    
    C'est parce qu'il y a une marge autour de l'en-tête. Une marge est l'espace entre l'élément (dans ce cas un en-tête) et les autres éléments qui l'entourent.
    
    Tu peux réduire la marge avec ce code:
    
        padding: 10px;
        
    
    ![capture d'écran](images/wanted-h1-margin-small.png)

+ Tu peux également souligner ta rubrique:
    
        text-decoration: underline;