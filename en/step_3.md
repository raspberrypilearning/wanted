## Styling images

Let's improve the style of the image in the poster.

--- task ---
Underneath the CSS for `div`, add another CSS style that will apply to images.

--- code ---
---
language: css
line_numbers: true
line_number_start: 1
line_highlights: 8-10
---
div {
  text-align: center;
  overflow: hidden;
  border: 2px solid black;
  width: 300px;
  background: yellow;
}
img {

}
--- /code ---

--- /task ---

--- task ---

Any CSS properties you add to this `img` style will apply to images.

Add this code to set the width of the image:

--- code ---
---
language: css
line_numbers: true
line_number_start: 8
line_highlights: 9
---
img {
	width: 100px;
}
--- /code ---
--- /task ---

--- task ---

Press **Run** and you'll see that the size of the image changes, so that its width is 100 pixels.

--- /task ---

--- task ---
Add a border around the image:

--- code ---
---
language: css
line_numbers: true
line_number_start: 8
line_highlights: 10
---
img {
	width: 100px;
	border: 1px solid black;
}
--- /code ---

--- /task ---

Have you noticed that there's not much space between the image and the border? The space between the image and its border is called **padding**.

![An image of a robot with a black border. The border is touching the robot image.](images/wanted-img-border.png)

--- task ---

Add some padding around the image:

--- code ---
---
language: css
line_numbers: true
line_number_start: 8
line_highlights: 11
---
img {
	width: 100px;
	border: 1px solid black;
	padding: 10px;
}
--- /code ---

--- /task ---

--- task ---
Press **Run** to see the extra padding

![An image of a robot with a black border. There is a gap between the robot image and the border.](images/wanted-img-padding.png)

--- /task ---