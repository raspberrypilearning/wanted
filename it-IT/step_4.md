## Dai stile alle tue immagini

Miglioriamo lo stile dell'immagine nel poster.

+ Al momento, non ci sono proprietà CSS per il tuo tag `<img>`, dunque aggiungiamone alcune!

	Per prima cosa, aggiungiamo il seguente codice sotto il CSS per il tuo 'div':

	```
	img {

	}
	```

	![screenshot](images/wanted-img-css.png)

+ Ora possiamo aggiungere proprietà CSS per le immagini tra le parentesi graffe `{` e `}`.

	Per esempio, aggiungi questo codice tra le parentesi graffe per stabilire la larghezza dell'immagine:

	```
	width: 100px;
	```

	Vedrai che la misura dell'immagine cambia, in modo che la sua larghezza diventi di 100 pixel.

	![screenshot](images/wanted-img-width.png)

+ Puoi anche aggiungere un bordo attorno all'immagine con questo codice:

	```
	border: 1px solid black;
	```

+ Hai notato che non c'è molto spazio tra l'immagine e il bordo?

	![screenshot](images/wanted-img-border.png)

	Puoi risolvere il problema aggiungendo dell'imbottitura attorno all'immagine:

	```
	padding: 10px;
	```

	Padding (imbottitura) è lo spazio tra il contenuto (in questo caso un'immagine) e il suo bordo.

	![screenshot](images/wanted-img-padding.png)

	Cosa succederebbe, secondo te, se cambiassi l'imbottitura a '50px'?
