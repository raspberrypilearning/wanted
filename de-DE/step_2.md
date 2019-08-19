## Styling your poster

Lass uns damit beginnen, den CSS Code für das Poster zu bearbeiten.

+ Öffne diesen Trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Das Projekt sollte so aussehen:
    
    ![Screenshot](images/wanted-starter.png)

+ Klicke auf den “style.css” Reiter. Du wirst sehen, dass es bereits CSS Eigenschaften für `div` gibt, welche die verschiedenen Teile des Posters enthalten.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Lass uns damit beginnen, die `text-align` (Textausrichtung) Eigenschaften zu verändern:
    
        text-align: center;
        
    
    Was passiert, wenn du das Wort center `center` (Mitte) zu `left` (links) oder `right` (rechts) änderst?

+ Wie sieht es mit der `border` (Rand) Eigenschaft aus?
    
        border: 2px solid black;
        
    
    `2px` in the code above means 2 pixels. What happens when you change `2px solid black` to `4px dotted red`?

+ Change the `width` of the poster to `400px`. What happens to the poster?

+ Let's add some CSS to set the background colour of the poster. Go to the end of line 5 of your code and press return, so that you have a new blank line.
    
    ![Screenshot](images/wanted-newline.png)
    
    Type the following code on your new blank line:
    
        background: yellow;
        
    
    Make sure that you type in the code *exactly* as it is above. You should notice that the background of the `<div>` is now yellow.
    
    ![Screenshot](images/wanted-background.png)