# AccordionPureCSS

/*___RU___*/
Шаг 1: Скачиваем CSS файл.

Шаг 2: Связываем документ с CSS файлом.
Пример:
&lt;head&gt;
    &lt;link rel="stylesheet" href="*Путь до CSS*"&gt;
&lt;/head&gt;

Шаг 3: Добавляем в разметку HTML обётрку нашего аккордиона, чтобы изолировать его от остального документа и не поламать ваши связи.
Пример:
/*HTML*/
&lt;div class="accordion-wrapper"&gt;

&lt;/div&gt;
/*HTML*/

Шаг 4: Добавляем список в обёртку, состоящий из n элементов, где n - количество
элементов вашего списка. !!!Аккордеон рассчитан на нечётное количество элементов,
если вам необходимо чётное количество см. шаг 7.1!!!
Пример:
&lt;ul class="accordion-stuff"&gt;
            &lt;li&gt;&lt;/li&gt;
            &lt;li&gt;&lt;/li&gt;
            &lt;li&gt;&lt;/li&gt;
&lt;/ul&gt;

Шаг 5: В каждый из элементов добавляем по 1 картинке.
Пример:
&lt;li&gt;&lt;img src="" class="accordion-img">&lt;/li&gt;
&lt;li&gt;&lt;img src="" class="accordion-img">&lt;/li&gt;
&lt;li&gt;&lt;img src="" class="accordion-img">&lt;/li&gt;

Шаг 6: Связываем картинки с тегами.
Пример:
&lt;li&gt;&lt;img src="*Путь до картинки 1*" class="accordion-img">&lt;/li&gt;
&lt;li&gt;&lt;img src="*Путь до картинки 2*" class="accordion-img">&lt;/li&gt;
&lt;li&gt;&lt;img src="*Путь до картинки 3*" class="accordion-img">&lt;/li&gt;

Шаг 7: Меняем в CSS файле "центральный элемент". (Строки 33, 37, 41).
Выставляя туда цифру: k, в зависимости от количества элементов вашего списка: n.
k = n /2 + 0.5

Шаг 7.1 (четное количество): Закоментируйте строки с 33 до 43.
(Не, ну а чо, мог бы и ещё 1 элементик добавить или 1 убрать)


Пример работы в index.html
UзU