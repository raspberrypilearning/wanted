## Überschriften gestalten

Lass uns den Stil von der `<h1>` Überschrift verbessern.

+ Füge den folgenden Code unterhalb des CSS deines Bildes ein:
    
        h1 {
        
        }
        
    
    Hier wirst du die CSS Eigenschaften für deine Hauptüberschrift `<h1>` einfügen.

+ Um die Schriftart deiner `<h1>` Überschriften zu ändern, fügst du den folgenden Code zwischen den geschweiften Klammern ein:
    
        font-family: Impact;
        

+ Du kannst auch die Größe deiner Überschrift ändern:
    
        font-size: 50pt;
        

+ Hast du bemerkt, dass es eine große Lücke zwischen der `<h1>` Überschrift und den Dingen um sie herum gibt?
    
    ![Screenshot](images/wanted-h1-margin.png)
    
    Dies liegt daran, dass sich um die Überschrift ein Rand befindet. Ein Rand ist der Abstand zwischen einem Element (in diesem Fall der Überschrift) und den anderen Dingen um es herum.
    
    Du kannst den Rand mit diesem Code kleiner machen:
    
        margin: 10px;
        
    
    ![Screenshot](images/wanted-h1-margin-small.png)

+ Du kannst die Überschrift auch unterstreichen:
    
        text-decoration: underline;