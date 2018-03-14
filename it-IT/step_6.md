## Dare stile all'intestazione

Miglioriamo lo stile dell'intestazione `<h1>`.

+ Aggiungiamo il seguente codice sotto il CSS della tua immagine:

	```
	h1 {

	}
	```

	Qui è dove aggiungerai proprietà CSS per la tua intestazione principale `<h1>`.

+ Per cambiare la fonte della tua intestazione `<h1>`, aggiungi il seguente codice tra parentesi graffe:

	```
	font-family: Impact;
	```

+ Puoi anche cambiare la misura dell'intestazione:

	```
	font-size: 50pt;
	```

+ Hai notato che c'è una grande spazio tra l'intestazione `<h1>` e il resto degli elementi attorno a essa?

	![screenshot](images/wanted-h1-margin.png)

	Questo succede perché c'è un margine attorno all'intestazione. Un margine è lo spazio tra l'elemento (in questo caso l'intestazione) e il resto delle cose attorno a esso.

	Puoi rimpicciolire il margine con questo codice:

	```
	margin: 10px;
	```

	![screenshot](images/wanted-h1-margin-small.png)

+ Puoi anche sottolineare la tua intestazione:

	```
	text-decoration: underline;
	```
