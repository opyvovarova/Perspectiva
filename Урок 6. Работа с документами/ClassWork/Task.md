﻿1) Создайте две кнопки: "Удалить все параграфы", "Добавить новый параграф". Создайте соответствующие обработчики события для этих кнопок. Вставлять и удалять параграфы нужно из тега <body>. 

2) Дан ненумерованый список элементов и параграф:

```html
<ul>
    <li>Text1</li>
    <li>Text2</li>
    <li>Text3</li>
    <li>Text4</li>
    <li>Text5</li>
    <li>Text6</li>
    <li>Text7</li>
    <li>Text8</li>
    <li>Text9</li>
    <li>Text10</li>
</ul>

<p id="output"></p>
```
а) Напишите код, который прочитает все содержимое каждого тега li, сформирует строку вида : "Text1Text2Text3...." и вывидет эту строку в параграф c id="output".  

б) Напишите код, который вместо текста ставит ссылку (``` <a href="#">Link</a> ```) в каждый тег ``` <li> ```.
