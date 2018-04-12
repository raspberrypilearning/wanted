## تحديد أنماط الملصق

لنبدأ بتحرير تعليمات CSS البرمجية للملصق.



+ افتح مشروع trinket هذا: <a target="_blank" href="http://jumpto.cc/web-wanted" target="_blank">jumpto.cc/web-wanted</a>. 

	سيكون المشروع بالشكل التالي:
	
	![screenshot](images/wanted-starter.png)

+ انقر فوق علامة التبويب "style.css". ستلاحظ أنه توجد خصائص CSS بالفعل للوسم `div` الذي يتضمن أجزاءً مختلفة للملصق.

	```
	div {
		;text-align: center
	    ;overflow: hidden
	    :border ;2px solid black
	    :width 300px;‎
    }	
	```

+ لنبدأ بتغيير الخاصية `text-align`:

	```
	;text-align: center
	```
	
	ماذا سيحدث عندما تغيِّر الكلمة `center` إلى `left` أو `right`؟

+ ماذا عن الخاصية `border`؟

	```
	:border ;2px solid black
	```

	`2px` الموجودة في التعليمة البرمجية أعلاه تعني وحدتَي بكسل. ماذا سيحدث عندما تغيِّر `2px solid black` إلى `4px dotted red`؟

+ غيِّر قيمة `width` للملصق إلى `400px`. ماذا حدث للملصق؟

+ لنضِف بعض خصائص CSS لتعيين لون خلفية الملصق. انتقل إلى نهاية السطر 5 من التعليمات البرمجية واضغط على المفتاح (Return) لتحصل على سطر جديد فارغ.

	![screenshot](images/wanted-newline.png)

	اكتب التعليمة البرمجية التالية في السطر الجديد الفارغ:

	```
	;background: yellow
	```

	تأكد من كتابة التعليمة البرمجية _تمامًا_ كما هو موضح أعلاه. ستلاحظ الآن أن خلفية الوسم `<div>` أصبحت صفراء.

	![screenshot](images/wanted-background.png)

