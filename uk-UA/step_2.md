## Дизайн твого плакату

Почнемо з редагування коду CSS для плаката.

+ Відкрий цей проєкт trinket: <a target="_blank" href="http://jumpto.cc/web-wanted">jumpto.cc/web-wanted</a>.
    
    Проєкт має виглядати так:
    
    ![знімок екрана](images/wanted-starter.png)

+ Клацни на вкладці "style.css". Ти побачиш, що для `div` вже існують властивості CSS, що відносяться до різних частин плаката.
    
        div {
            text-align: center;
            overflow: hidden;
            border: 2px solid black;
            width: 300px;
        }   
        

+ Давай почнемо зі зміни властивості `text-align`:
    
        text-align: center;
        
    
    Що трапиться, якщо ти зміниш слово `center` на `left` чи `right`?

+ А як щодо властивості `border`?
    
        border: 2px solid black;
        
    
    `2px` в коді вище означає 2 пікселі. Що трапиться, якщо ти зміниш `2px solid black` на `4px dotted red`?

+ Зміни ширину (`width`) плаката до `400px`. Що трапиться з плакатом?

+ Давай додамо код CSS, щоб встановити фоновий колір плаката. Перейди в кінець рядка 5 свого коду та натисни Enter, щоб з'явився новий пустий рядок.
    
    ![знімок екрана](images/wanted-newline.png)
    
    Введи наступний код в новий пустий рядок:
    
        background: yellow;
        
    
    Переконайся, що вводиш код *точно* так, як це показано вище. Ти маєш помітити, що фон `<div>` став жовтим.
    
    ![знімок екрана](images/wanted-background.png)