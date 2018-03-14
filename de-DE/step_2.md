## Poster Gestaltung

Lass uns damit beginnen, den CSS Code für das Poster zu bearbeiten.

+ Dieses Trinket öffnen: <a href="http://jumpto.cc/web-wanted" target="_blank">jumpto.cc/web-wanted</a>. 

	Das Projekt sollte so aussehen:
	
	![screenshot](images/wanted-starter.png)

+ Klicke auf den "style.css" (Stil) Reiter. Du wirst sehen, dass es bereits CSS Eigenschaften für `div` gibt, welche die verschiedenen Teile des Posters enthalten.

	```
	div {
		Textausrichtung: Mitte;
	    Überhang: versteckt;
	    Rand: 2px durchgehend schwarz; 
	    Breite: 300px;
    }	
	```

+ Lass uns damit beginnen, die `text-align` (Textausrichtung) Eigenschaften zu verändern:

	```
	Textausrichtung: Mitte;
	```
	
	Was passiert, wenn du das Wort `center` (Mitte) zu `left` (links) oder `right` (rechts) änderst?

+ Wie sieht es mit der `border` (Rand) Eigenschaft aus?

	```
	Rand: 2px durchgehend schwarz;
	```

	`2px` in dem o.g. Code bedeutet: 2 Pixel. Was passiert, wenn du `2px solid black` (2px durchgehend schwarz) zu `4px dotted red` (4px rot gepunktet) änderst?

+ Ändere die `width` Posterbreite zu `400px`. Was geschieht dann mit dem Poster?

+ Lass uns jetzt CSS hinzufügen, um die Hintergrundfarbe des Posters zu gestalten. Gehe zum Ende der Zeile 5 deines Codes und drücke die Eingabetaste, damit du eine neue, leere Zeile erhältst.

	![screenshot](images/wanted-newline.png)

	Tippe den folgenden Code in deine neue, leere Zeile ein:

	```
	Hintergrund: gelb;
	```

	Achte darauf, dass du den Code _exakt_ so eintippst, wie er oben geschrieben ist. Du solltest jetzt bemerken können, dass der Hintergrund für `<div>` nun gelb ist.

	![screenshot](images/wanted-background.png)
