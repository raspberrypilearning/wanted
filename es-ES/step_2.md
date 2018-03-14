## Dar estilo a tu póster

Empezaremos por editar el código CSS del póster.

+ Abre este trinket: <a href="http://jumpto.cc/web-wanted" target="_blank">jumpto.cc/web-wanted</a>. Si estás leyendo este proyecto online, también puedes usar la versión incrustada de este trinket que encontrarás a continuación.

<div class="trinket">
	<iframe src="https://trinket.io/embed/html/58318bee1f" width="100%" height="550" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
	</iframe>
</div>

+ Haz clic en la pestaña "style.css". Verás que ya hay propiedades CSS para el `div` que contiene las diferentes partes del póster.

	```
	div {
		text-align: center;
	    overflow: hidden;
	    border: 2px solid black;
	    width: 300px;
    }	
	```

+ Empezaremos por cambiar la propiedad `text-align` (alineación del texto):

	```
	text-align: center;
	```
	
	¿Qué pasa si cambias la palabra `center` (centro) por `left` (izquierda) o por `right` (derecha)?

+ ¿Y la propiedad `border` (borde)?

	```
	border: 2px solid black;
	```

	`2px` en el código de arriba significa 2 píxeles. ¿Qué ocurre cuando cambias `2px solid black` (2px negro sólido) por `4px dotted red` (4px rojo punteado)?

+ Cambia el `width` (ancho) del póster a `400px`. ¿Qué le ocurre al póster?

+ Vamos a añadir algo de CSS para establecer el color de fondo del póster. Ve al final de la línea 5 del código y presiona la tecla de retorno, para que aparezca una nueva línea en blanco.

	![screenshot](images/wanted-newline.png)

	Escribe el siguiente código en la nueva línea en blanco:

	```
	background: yellow;
	```

	Asegúrate de escribir el código _exactamente_ igual que arriba. Te habrás dado cuenta de que ahora el fondo del `<div>` es amarillo.

	![screenshot](images/wanted-background.png)
