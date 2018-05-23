## Σχεδίαση της αφίσας σου

Ας αρχίσουμε με την επεξεργασία του κώδικα CSS για την αφίσα.

+ Άνοιξε αυτό το trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Το έργο πρέπει να μοιάζει έτσι:
    
    ![screenshot](images/wanted-starter.png)

+ Κάνε κλικ στην καρτέλα "style.css". Θα παρατηρήσεις ότι υπάρχουν ήδη ιδιότητες CSS για το `div` που περιέχει τα διάφορα μέρη της αφίσας.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Ας ξεκινήσουμε τροποποιώντας την ιδιότητα `text-align`:
    
        text-align: center;
        
    
    Τι συμβαίνει όταν αλλάζεις τη λέξη `center` σε `left` ή `right`;

+ Τι λες για την ιδιότητα `border`;
    
        border: 2px solid black;
        
    
    `2px` στον ανωτέρω κώδικα σημαίνει 2 εικονοστοιχεία. Τι συμβαίνει όταν αλλάζεις την τιμή `2px solid black` σε `4px dotted red`;

+ Change the `width` of the poster to `400px`. What happens to the poster?

+ Let's add some CSS to set the background colour of the poster. Go to the end of line 5 of your code and press return, so that you have a new blank line.
    
    ![screenshot](images/wanted-newline.png)
    
    Type the following code on your new blank line:
    
        background: yellow;
        
    
    Make sure that you type in the code *exactly* as it is above. You should notice that the background of the `<div>` is now yellow.
    
    ![screenshot](images/wanted-background.png)