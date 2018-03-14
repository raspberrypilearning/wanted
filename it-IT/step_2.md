## Dai stile al tuo poster

Iniziamo a modificare il codice CSS del poster.

+ Apri questo trinket: <a href="http://jumpto.cc/web-wanted" target="_blank">jumpto.cc/web-wanted</a>.

	Il progetto dovrebbe apparire così:

	![screenshot](images/wanted-starter.png)

+ Clicca sul tab "style.css". Noterai che ci sono già proprietà CSS per il 'div' contenente le diverse parti del poster.

	```
	div {
		text-align: center;
	    overflow: hidden;
	    border: 2px solid black;
	    width: 300px;
    }
	```

+ Iniziamo ad alterare la proprietà 'text-align' (allineamento del testo):

	```
	text-align: center;
	```

	Che succede quando cambi la parola 'center' (centro) a 'left' (sinistra) o 'right' (destra)?

+ E la proprietà 'border' (bordo)?

	```
	border: 2px solid black;
	```

	'2px' nel codice sopra significa 2 pixel. Cosa succede quando cambi '2px solid black' (2px nero tinta unita) per '4px dotted red' (4px rosso a puntini)?

+ Cambia la 'width' (larghezza) del poster a '400px'. Cosa succede al poster?

+ Aggiungiamo alcuni CSS per stabilire il colore di sfondo del poster. Vai alla fine della riga 5 del tuo codice e premi il tasto di ritorno, in modo da avere una nuova linea vuota.

	![screenshot](images/wanted-newline.png)

	Digita il seguente codice sulla tua nuova linea vuota:

	```
	background: yellow;
	```

	Assicurati di digitare il codice_esattamente_come è sopra. Dovresti notare che lo sfondo del `<div>` è adesso giallo.

	![screenshot](images/wanted-background.png)
