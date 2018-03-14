## Dar estilo a las imágenes

Vamos a mejorar el estilo de la imagen del póster.

+ Ahora mismo, no hay ninguna propiedad de CSS para la etiqueta `<img>`, así que ¡vamos a añadir algunas!

	En primer lugar, añade el siguiente código por debajo del CSS para tu div:

	```
	img {

	}
	```

	![screenshot](images/wanted-img-css.png)

+ Ahora podemos añadir a las imágenes propiedades de CSS entre las llaves `{` y `}`.

	Por ejemplo, añade este código entre las llaves para establecer el ancho ("width") de la imagen:

	```
	width: 100px;
	```

	Verás que el ancho de la imagen cambia, para que sea de 100 píxeles.

	![screenshot](images/wanted-img-width.png)

+ También puedes añadir un borde alrededor de la imagen con este código:

	```
	border: 1px solid black;
	```

+ ¿Te has dado cuenta de que no hay demasiado espacio entre la imagen y el borde?

	![screenshot](images/wanted-img-border.png)

	Puedes arreglar esto añadiendo un poco de relleno alrededor de la imagen:

	```
	padding: 10px;
	```

	Padding (relleno) es el espacio entre el contenido (en este caso una imagen) y su borde.

	![screenshot](images/wanted-img-padding.png)

	¿Qué crees que pasaría si cambiases el relleno a `50px`?
