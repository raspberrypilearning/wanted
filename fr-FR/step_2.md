## Styling your poster

Let's start by editing the CSS code for the poster.



+ Open this trinket: <a target="_blank" href="http://jumpto.cc/web-wanted" target="_blank">jumpto.cc/web-wanted</a>. 

	The project should look like this:
	
	![screenshot](images/wanted-starter.png)

+ Click on the "style.css" tab. You'll notice that there are already CSS properties for the `div` containing the different parts of the poster.

	```
	div {
		text-align: center;
	    overflow: hidden;
	    border: 2px solid black;
	    width: 300px;
    }	
	```

+ Let's start by altering the `text-align` property:

	```
	text-align: center;
	```
	
	What happens when you change the word `center` to `left` or `right`?

+ How about the `border` property?

	```
	border: 2px solid black;
	```

	`2px` in the code above means 2 pixels. What happens when you change `2px solid black` to `4px dotted red`?

+ Change the `width` of the poster to `400px`. What happens to the poster?

+ Let's add some CSS to set the background colour of the poster. Go to the end of line 5 of your code and press return, so that you have a new blank line.

	![screenshot](images/wanted-newline.png)

	Type the following code on your new blank line:

	```
	background: yellow;
	```

	Make sure that you type in the code _exactly_ as it is above. You should notice that the background of the `<div>` is now yellow.

	![screenshot](images/wanted-background.png)

