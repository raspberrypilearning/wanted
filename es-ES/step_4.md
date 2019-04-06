## Diseño de las imágenes

Mejoremos el estilo de la imagen en el cartel.

+ En este momento, no hay propiedades CSS para tu etiqueta `<img>`, ¡así que vamos a añadir algunas!
    
    Primero, añade el siguiente código debajo del CSS para su div:
    
        img {
        
        }
        
    
    ![captura de pantalla](images/wanted-img-css.png)

+ Ahora podemos añadir propiedades CSS para las imágenes entre los corchetes.
    
    Por ejemplo, añade este código entre los corchetes para establecer el ancho de la imagen:
    
        width: 100px;
        
    
    Verás que el tamaño de la imagen cambia, de modo que su ancho es de 100 píxeles.
    
    ![captura de pantalla](images/wanted-img-width.png)

+ También puedes añadir un borde alrededor de la imagen con este código:
    
        border: 1px solid black;
        

+ ¿Te has dado cuenta de que no hay mucho espacio entre la imagen y el borde?
    
    ![captura de pantalla](images/wanted-img-border.png)
    
    Puedes arreglarlo añadiendo un poco de relleno alrededor de la imagen:
    
        padding: 10px;
        
    
    El relleno es el espacio entre el contenido (en este caso una imagen) y su borde.
    
    ![captura de pantalla](images/wanted-img-padding.png)
    
    ¿Qué crees que sucedería si cambiaras el relleno a `50px`?