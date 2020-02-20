## Stylisation des images

Améliorons le style de l'image dans l'affiche.

+ Pour l'instant, il n'y a pas de propriétés CSS pour ta balise `<img>`, ajoutons-en !
    
    Premièrement, ajoute le code suivant sous le CSS pour ton div :
    
        img {
        
        }
        
    
    ![capture d'écran](images/wanted-img-css.png)

+ Nous pouvons maintenant ajouter des propriétés CSS pour les images entre les accolades.
    
    Par exemple, ajoute ce code entre les accolades pour définir la largeur de l'image :
    
        width: 100px;
        
    
    Tu verras que la taille de l'image change, de sorte que sa largeur est de 100 pixels.
    
    ![capture d'écran](images/wanted-img-width.png)

+ Tu peux également ajouter une bordure autour de l'image avec ce code :
    
        border: 1px solid black;
        

+ As-tu remarqué qu'il n'y a pas beaucoup d'espace entre l'image et la bordure ?
    
    ![capture d'écran](images/wanted-img-border.png)
    
    Tu peux résoudre ce problème en ajoutant des éléments de remplissage autour de l'image :
    
        padding: 10px;
        
    
    Le remplissage est l'espace entre le contenu (dans ce cas une image) et sa bordure.
    
    ![capture d'écran](images/wanted-img-padding.png)
    
    Que penses-tu qu'il se passerait si tu changeais le remplissage en ` 50px ` ?