## अपने पोस्टर को स्टाइल करना

आइए पोस्टर के लिए CSS कोड को एडिट करके शुरू करें।

+ इस trinket को खोलें: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>।
    
    प्रोजेक्ट इस तरह दिखना चाहिए:
    
    ![स्क्रीनशॉट](images/wanted-starter.png)

+ "style.css" टैब पर क्लिक करें। आप देखेंगे कि पोस्टर के विभिन्न भागों वाले `div` के लिए पहले से ही CSS प्रॉपर्टीज हैं।
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ आईए `text-align` प्रॉपर्टी को बदलकर शुरू करें:
    
        text-align: center;
        
    
    जब आप शब्द `center (बीच में)` को `left (बाएँ)` या `right (दाएँ)` में बदलते हैं तो क्या होता है?

+ `border` प्रॉपर्टी का क्या होता है?
    
        border: 2px solid black;
        
    
    ऊपर दिए गए कोड में `2px` का मतलब 2 पिक्सल है। क्या होता है जब आप `2px solid black` को `4px dotted red` में बदलते हैं?

+ पोस्टर की `width (चौड़ाई)` को `400px` में बदलें। पोस्टर का क्या होता है?

+ चलिए पोस्टर की पृष्ठभूमि का रंग सेट करने के लिए कुछ CSS जोड़ते हैं। अपने कोड की लाइन 5 के अंत में जाएं और return दबाएं, ताकि आपके पास एक नई खाली लाइन हो।
    
    ![स्क्रीनशॉट](images/wanted-newline.png)
    
    अपनी नई खाली लाइन पर निम्न कोड टाइप करें:
    
        background: yellow;
        
    
    सुनिश्चित करें कि आप कोड *ठीक से* टाइप करते हैं जैसा कि यह ऊपर है। आपको ध्यान देना चाहिए कि `<div>` की पृष्ठभूमि अब पीली है।
    
    ![स्क्रीनशॉट](images/wanted-background.png)