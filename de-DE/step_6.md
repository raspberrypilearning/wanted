## Styling headings

Let's improve the style of the `<h1>` heading.



+ Add the following code underneath your image's CSS:

	```
	h1 {

	}
	```

	This is where you'll add CSS properties for your main `<h1>` heading.

+ To change the font of your `<h1>` headings, add the following code between the curly brackets:

	```
	font-family: Impact;
	```

+ You can also change the size of the heading:

	```
	font-size: 50pt;
	```

+ 	Have you noticed that there's a big space between the `<h1>` heading and the stuff around it?

	![screenshot](images/wanted-h1-margin.png)

	This is because there's a margin around the heading. A margin is the space between the element (in this case a heading) and the other stuff around it.

	You can make the margin smaller with this code:

	```
	margin: 10px;
	```

	![screenshot](images/wanted-h1-margin-small.png)

+ You can also underline your heading:

	```
	text-decoration: underline;
	```

