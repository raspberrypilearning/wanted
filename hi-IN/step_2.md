## आपके पोस्टर को स्टाइल देना

चलिए पोस्टर के लिए CSS कोड को एडिट करने से आरंभ करें।



+ इस ट्रिंकेट को खोलें: <a target="_blank" href="http://jumpto.cc/web-wanted" target="_blank">jumpto.cc/web-wanted</a>. 

	प्रोजेक्ट कुछ इस प्रकार दिखाई देना चाहिए:
	
	![screenshot](images/wanted-starter.png)

+ "style.css" टैब पर क्लिक करें। आप देखेंगे कि पोस्टर के सभी भागों युक्त `div` के लिए CSS गुण पहले से ही मौजूद हैं।

	```
	div {
		text-align: center;
	    overflow: hidden;
	    border: 2px solid black;
	    width: 300px;
    }	
	```

+ चलिए `text-align` गुण में परिवर्तन करने से आरंभ करें:

	```
	text-align: center;
	```
	
	जब आप शब्द `center` (केंद्र) को `left` (बाएँ) या `right` (दाएँ) में परिवर्तित करते हैं तो क्या होता है?

+ `border` (सीमा) गुण कैसा है?

	```
	border: 2px solid black;
	```

	उपरोक्त कोड में `2px` का अर्थ है 2 पिक्सल्स। जब आप `2px solid black` को `4px dotted red` में परिवर्तित करते हैं तो क्या होता है?

+ पोस्टर की `चौड़ाई` को `400px` करें। पोस्टर के साथ क्या होता है?

+ चलिए पोस्टर का बैकग्राउंड रंग सेट करने के लिए कुछ CSS लिखें। अपने कोड की 5वीं पंक्ति के अंत में जाएँ और रिटर्न (return) दबाएँ, ताकि आप एक नई खाली पंक्ति पर पहुँच जाएँ।

	![screenshot](images/wanted-newline.png)

	आपकी नई खाली पंक्ति में निम्नलिखित कोड लिखें:

	```
	background: yellow;
	```

	यह सुनिश्चित करें कि आप _exactly_ (बिल्कुल) उपर की तरह कोड टाइप करते हैं।  आपको देखना चाहिए कि `<div>` का बैकग्राउंड अब पीला है।

	![screenshot](images/wanted-background.png)

