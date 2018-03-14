## Bilder gestalten

Lass uns den Stil des Posterbilds verbessern.

+ Derzeit gibt es keine CSS Eigenschaften für dein `<img>` Tag, lass uns also noch mehr hinzufügen!

	Als erstes, füge den folgenden Code unterhalb des CSS für dein div:

	```
	img {

	}
	```

	![screenshot](images/wanted-img-css.png)

+ Wir können jetzt die CSS Eigenschaften für Bilder zwischen `{` and `}` geschweiften Klammern setzen.

	Zum Beispiel: Füge disen Code zwischen die geschweiften Klammern ein, um die Bildbreite einzustellen:

	```
	Breite: 100px;
	```

	Du wirst sehen, dass sich die Bildgröße verändern wird, sodass die Bildbreite jetzt 100 Pixel beträgt.

	![screenshot](images/wanted-img-width.png)

+ Du kannst auch mit Hilfe dieses Codes einen Rand rund um das Bild machen:

	```
	Rand: 1px durchgehend schwarz;
	```

+ Hast du bemerkt, dass nicht viel Platz zwischen dem Bild und dem Rand besteht?

	![screenshot](images/wanted-img-border.png)

	Du kannst dies beheben, indem du etwas Füllung rund um das Bild einfügst:

	```
	Füllung: 10px;
	```

	Die Füllung ist der Raum zwischen dem Inhalt (in diesm Fall ein Bild) und dessen Rand.

	![screenshot](images/wanted-img-padding.png)

	Was meinst du wird passieren, wenn du die Füllung zu `50px` ändern würdest?
