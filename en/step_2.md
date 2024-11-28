## Styling your poster

Let's start by editing the CSS code for the poster.

--- task ---

Open the [starter project](https://editor.raspberrypi.org/en/projects/wanted-starter){:target="_blank"}

--- /task ---

--- task ---

Click on the "style.css" file and find the `text-align` property. 

Change the word `center` to `left` or `right`, then press the **Run** button. What happens?

--- code ---
---
language: html
line_numbers: true
line_number_start: 1
line_highlights: 3
---
div {
  text-align: center;
  overflow: hidden;
  border: 2px solid black;
  width: 300px;
}
--- /code ---
	


--- /task ---

--- task ---

Change the `border` property to `4px dotted red`. What happens?

--- code ---
---
language: html
line_numbers: true
line_number_start: 1
line_highlights: 3
---
div {
  text-align: center;
  overflow: hidden;
  border: 2px solid black;
  width: 300px;
}
--- /code ---
--- /task ---

--- task ---

Change the `width` of the poster to `400px`. What happens?

--- /task ---

--- task --- 
Add this code on the line below the width (but before the bracket `}`):

--- code ---
---
language: html
line_numbers: true
line_number_start: 1
line_highlights: 6
---
div {
  text-align: center;
  overflow: hidden;
  border: 2px solid black;
  width: 300px;
  background: yellow;
}
--- /code ---

--- /task ---

--- task ---
What do you think will happen? Press the **Run** button to see whether you were right.

--- /task ---

--- task ---
Add another line of code to change the border radius. Predict what you think will happen, then press the **Run** button to see whether you were right. 


--- code ---
---
language: html
line_numbers: true
line_number_start: 1
line_highlights: 7
---
div {
  text-align: center;
  overflow: hidden;
  border: 2px solid black;
  width: 300px;
  background: yellow;
  border-radius: 40px;
}
--- /code ---
--- /task ---
