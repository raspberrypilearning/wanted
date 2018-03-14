## Style ton image

Continuons en améliorant l'image de ton poster.

+ Pour l'instant. il n'y a pas de propriétés CSS pour ton tag `<img>`, et si on en rajoutais une!

	Premièrement, ajoute le code CSS suivant après le code pour ton `div`

	```
	img {

	}
	```

	![screenshot](images/wanted-img-css.png)

+ On peux maintenant rajouter les propriétés CSS pour les images entre les crochets `{` et `}`

	Par exemple, ajoute ce code entre les crochets pour définir la longueur de ton image:

	```
	width: 100px;
	```

	Tu devrais voir la taille de ton image changer, sa longueur est maintenant de 100 pixels.

	![screenshot](images/wanted-img-width.png)

+ Tu peux aussi ajouter une bordure a ton image avec ce code:

	```
	border: 1px solid black;
	```

+ As-tu remarqué qu'il n'y a pas beaucoup d'espace entre l'image et la bordure?

	![screenshot](images/wanted-img-border.png)

	Tu peux ajouter plus d'espace autour de l'image en utilisant la propriété `padding`:

	```
	padding: 10px;
	```

	`padding` est l'espacement entre le contenu (dans notre cas, l'image) et sa bordure.

	![screenshot](images/wanted-img-padding.png)

	Que se passe t'il si tu changes la valeur du `padding` a `50px`?
