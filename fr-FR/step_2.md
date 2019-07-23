## Styliser ton poster

Commençons par éditer le code CSS de l’affiche.

+ Ouvre ce trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Le projet devrait ressembler à ceci:
    
    ![capture d'écran](images/wanted-starter.png)

+ Clique sur l'onglet "style.css". Tu remarqueras qu'il existe déjà des propriétés CSS pour le ` div ` contenant les différentes parties de l'affiche.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Commençons par modifier la propriété ` text-align `:
    
        text-align: center;
        
    
    Que se passe-t-il lorsque tu remplace le mot ` centre ` par `à gauche ` ou ` à droite ` ?

+ Qu'en est-il de la propriété bordure ` `?
    
        bordure: noir 2px;
        
    
    ` 2px ` dans le code ci-dessus signifie 2 pixels. Que se passe-t-il lorsque tu changes ` 2 pixels noir uni ` à ` 4px en pointillé rouge ` ?

+ Changer la ` largeur ` de l'affiche à ` 400px ` . Qu'advient-il de l'affiche?

+ Ajoutons quelques CSS pour définir la couleur de fond de l'affiche. Allez à la fin de la ligne 5 de ton code et appuie sur Entrée pour avoir une nouvelle ligne vierge.
    
    ![capture d'écran](images/wanted-newline.png)
    
    Entre le code suivant dans ta nouvelle ligne vide:
    
        background: silver;
        
    
    Assure-toi d'entrer le code * exactement * comme ci-dessus. Tu devrais remarquer que l’arrière-plan du `<div>` est maintenant jaune.
    
    ![capture d'écran](images/wanted-background.png)