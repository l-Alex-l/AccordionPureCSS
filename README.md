# AccordionPureCSS

/*___RU___*/
Шаг 1: Скачиваем CSS файл.

Шаг 2: Связываем документ с CSS файлом.
Пример:<br>
&lt;head&gt;<br>
    &lt;link rel="stylesheet" href="*Путь до CSS*"&gt;<br>
&lt;/head&gt;<br>

Шаг 3: Добавляем в разметку HTML обётрку нашего аккордиона, чтобы изолировать его от остального документа и не поламать ваши связи.
Пример:<br>
/*HTML*/<br>
&lt;div class="accordion-wrapper"&gt;<br>
<br>
&lt;/div&gt;<br>
/*HTML*/<br>

Шаг 4: Добавляем список в обёртку, состоящий из n элементов, где n - количество
элементов вашего списка.<br>
!!!Аккордеон рассчитан на нечётное количество элементов,
если вам необходимо чётное количество см. шаг 7.1!!!
Пример:<br>
&lt;ul class="accordion-stuff"&gt;<br>
            &lt;li&gt;&lt;/li&gt;<br>
            &lt;li&gt;&lt;/li&gt;<br>
            &lt;li&gt;&lt;/li&gt;<br>
&lt;/ul&gt;<br>

Шаг 5: В каждый из элементов добавляем по 1 картинке.
Пример:<br>
&lt;li&gt;&lt;img src="" class="accordion-img">&lt;/li&gt;<br>
&lt;li&gt;&lt;img src="" class="accordion-img">&lt;/li&gt;<br>
&lt;li&gt;&lt;img src="" class="accordion-img">&lt;/li&gt;<br>

Шаг 6: Связываем картинки с тегами.
Пример:<br>
&lt;li&gt;&lt;img src="*Путь до картинки 1*" class="accordion-img">&lt;/li&gt;<br>
&lt;li&gt;&lt;img src="*Путь до картинки 2*" class="accordion-img">&lt;/li&gt;<br>
&lt;li&gt;&lt;img src="*Путь до картинки 3*" class="accordion-img">&lt;/li&gt;<br>

Шаг 7: Меняем в CSS файле "центральный элемент". (Строки 33, 37, 41).
Выставляя туда цифру: k, в зависимости от количества элементов вашего списка: n.<br>
k = n /2 + 0.5

Шаг 7.1 (четное количество): Закоментируйте строки с 33 до 43.<br>
(Не, ну а чо, мог бы и ещё 1 элементик добавить или 1 убрать)


Пример работы в index.html<br>
UзU