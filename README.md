1 Урок - Вводный урок
	Памятка: обязательно понимать как работаю атрибуты к каждому тегу
	Вопросы: что нужно первоочередное знать и понимать про HTML?

2 Урок - Знакомство с HTML, базовая струтура, мета-теги:
	Памятка: 1) - основа 2) - Форматирование 3) - Семантика ссылка -    doca.guide
	Вопросы:

3 Урок - 
	Памятка - Семантика, валидность, доступность (отличие верстки от чисто блочным тегом div)
	Вопросы -

4 Урок - Глобальная струткура сайта 
	Памятка:
 	<header></header><!--Навигация-->
 	<main>
 	<div>
 	<article></article><!--Статья-->
 	<aside></aside> <!--Навигация-->
 	</div>
 	<section></section> <!--Разделы-->
 	<section></section> <!--Разделы-->
 	 alt+w - c помощью extension можем обвернуть в блочный тег выделенный фрагмент

 	Вопросы: Насколько критично верстать сайт div`ами в отличии от выстроенной структуры?

5 Урок - Теги для тестовых элементов: (h1-h6, p, q blockquoute)
	Памятка:
	Вопросы:

6 Урок - Теги для списков: (ul, ol, dl)
	Памятка:
	Вопросы: вставка текста в таблицы маштабно, reserved (?)

7 Урок - Вставка изображений: (img, picture, source, figure, figcapture)
	Памятка: разница между img и picture (знать как работает source внутри picture), figcaption - знать назначение тега (внутри figure) - это текстовая подпись к картинке
	Вопросы:

8 Урок - Видео и Аудио: (audio, video, source и атрибуты для них)
	Памятка: тег внутри вставки аудио и видео - controls (для отображения файла аудио на странице) иметь ввиду формат .webm для видео (удобство, если есть возможность формата), обратить внимание на конструкцию в index.html (внимание на построение video (с взаимодействием тега source)) (конструкция подходит и под audio).
	Атрибут loop - автозапуск трека по новой, атрибут autoplay для видео (убирается контролер и видео запускается видео автоматически). 
	Атрибут muted используется для запуска видео без звука, poster атрибут для видео (превью к видео, добавляется img=""). 
	Атрибут preload (имеет 3 режима - auto, metadata, none)  - нужен для того чтоб сообщить браузеру как нам загружать аудио или видео файл при открытии страницы
	Вопросы:

9 Урок - Ссылки и кнопки: (a и button)
	Памятка: знать как работают якорные ссылки, обратить внимание ка работает вставки номеров, почты и ПО вставкой в атрибут href="example@mail.ru" (необходимо для перехода по этой "ссылке" наэто ПО или телефон)
	Создание кнопки, тег - button: 
	атрибут type="" (submit и reset)
	знать как работает автофокус (нужен для удобства)
	disabled
	Вопросы: для чего используются атрибут type submit и reset

10 Урок - Таблицы: (table, th, tr, td, capture, thead, tbody, tfoot)
	Памятка: последнее время не используется
	Вопросы:

11 Урок - Формы: (form, fieldset, legend, label, input, select, textarea)
	Памятка: 
	Тег form: 
	aтрибут method (dialog, get, post) 
	атрибут name 
	атрибут autocomplete (on, off) - для использования автоматического ввода данных (после первого ввода данных запоминает и использовать в дальнейшем выбираем сами с помощью on или off)
	элемент формы button c атрибутом type (button, menu, reset, submit)
	Для более расширенного описания тегов использвать doca.guide
	Тег input:
	Teг select:
	Тег options:
	Тег textarea (форма для ввода текста):
	атрибут cols - необходим для размера поля
	атрибут rows - 
	Тег label (для подписи поля (формы)):
	атрибут for - 

	Вопросы: Как грамотно выстраивать структуру из этих тегов?

12 Урок - Поля Ввода: (различные значения атрибута type для input)
	Памятка: 
	разобрать значения input`а

	Вопросы:

13 Урок - Общие и полезные атрибуты: (id, class, style, title, tabindex)
	Памятка:
	атрибут id - 
	атрибут class - 
	атрибут style - 
	атрибут title - 
	атрибут tabindex - 
	Вопросы:

14 Урок - Пути подключения: (абсолютные и относительные)
	Памятка:
	абсолютный путь подключения - 
	относительный путь подключения - 
	Вопросы:

15 Урок - Знакомство с CSS, наследование, синтаксис, селекторы
	Памятка: 
	https://webdesign.tutsplus.com/the-30-css-selectors-you-must-memorize--net-16048t
	Наследование - 
	Синтаксис - 
	Селекторы - 
	Вопросы:

16 Урок - Приоритет селекторов
	Памятка: 
	Важный урок, основные элементы выписать с сайта по пунктам.
	Выписать обозначения айди, классов и т.д. чтоб не путаться 
	Приоритет: 
	1 -  1000 (inline style)
	2 -  100 (id) 
	3 -  10 (class, atribute, pseudo-class)
	4 -  1 (element, pseudo-element)
	!impotant (самый важный приоритет)
	Вопросы: 

17 Урок - БЭМ: блок, элемент, модификатор
	Памятка:
	БЭМ - (блок, элемент. модификатор)
	Блок - 
	Элемент - 
	Модификатор - 
	(последовательное использование класса с именем (последующие создаются с несколькими подчеркиваниями как структура) (подробнее изучить с доп. материалов) (блок->элемент))
	Урок (выстраивание структуры на основе БЭМ по сайту)
	Вопросы: Нормально ли использовать для первой практики методологию БЭМ чисто тегом div?

	ДЗ: Выстроить структуру сайта(на выбор) по методологии БЭМ с помощью div

18 Урок - Обнуление стилей браузера
	Памятка: 
	Запомнить для последующих уроков

	Вопросы: 
	Для чего отключать надо?
	Как влияет для дальнейшей работы обнуление стилей браузера? 
	Часто ли используется на практике?

19 Урок - Свойства редактирования шрифта и текста
	Памятка:
	Необходимо знать для разработки (отображения внешнего вида текста) 
	Свойства и атрибуты css:
	text-decoration - 
	text-shadow - 
	text-indent - 
	letter-spacing - 
	word-spacing - 
	white-space (важное свойство)- 

	справочник css (гугл свойства и справочник показывает все свойства с описанием)

	Вопросы:
	Часто ли используешь "Emmet"? Насколько экономит время при разработке? И есть ли лайфхак или шпарглака как запомнить основные элементы (теги, свойства, атрибуты) для работы?

20 Урок - Единицы измерения: px, em, rem, %, vh, vmin, vmax
	Памятка:
	Единицы измерения: 
	Абсолютные - 
	PX - 
	Относительные - EM и REM, % VH и VW, VMIN и VMAX (Важно при адаптивной верстке)
	EM и REM - 
	% - 
	VH - 
	VW - 
	VMIN - 
	VMAX - 
	Важный момент с браузерными настройками по default
	Написать размеры всех единиц измерений
	Вопросы: 

21 Урок - Подключение шрифтов: google fonts, font-face
	Памятка:
	Вопросы:

22 Урок - Основные свойства CSS на блочных и строчных объектах 
	Памятка:
	Вопросы:

23 Урок - Background
	Памятка:
	Вопросы:

24 Урок - Position
	Памятка:
	Вопросы:

25 Урок - Transform
	Памятка:
	Вопросы:

26 Урок - Transition
	Памятка:
	Вопросы:

27 Урок - Animation
	Памятка:
	Вопросы:

28 Урок - Flexbox
	Памятка:
	Вопросы:

29 Урок - Grid
	Памятка:
	Вопросы:

30 Урок - Псевдоклассы: hover, visitedm active, focus, first-child и т.п.
	Памятка:
	Вопросы:

31 Урок - Псевдоэлементы: before, after, first-line, first-letter
	Памятка:
	Вопросы:	

32 Урок - Ускорение верстки
	Памятка:

	Ctrl + Z - отмена действия.
	Ctrl + Y - возврат отмены. 
	Ctrl + X - вырезать.
	Ctrl + V - вставить.
	Shift + Alt + F - форматирование кода.
	End - перемещение к концу строки.
	Home - перемещение к началу строки.
	Ctrl + End - перемещение к концу страницы кода.
	Ctrl + Home - перемещение к началу страницы кода. 
	Alt - использование мульти курсора.
	Ctrl + Alt + стрелка вверх/вниз - использование мульти курсора строками.
	Shift + стрелка влево/вправо - выделение кода по символам.
	Ctrl + Shift + стрелка влево/вправо - выделение кода фрагментами.
	Alt + W - оборачивание кода тегами. 
	Ctrl + F - поиск по коду.
	Ctrl + Shift + F - поиск по всем файлам кода.
	Ctrl + Alt + E - копирование всех классов в CSS.
	F2 - смена тега.
	Shift+Alt+F - код выстраивается в лесенку, как надо
	Ctr+X - вырезается код ( строчка )
	End - перемещение в самый конец строки
	Home - перемещение в самое начало строки
	Ctr+End - перемещение в самый конец (низ) кода
	Ctr+Home - перемещение в самое начало (вверх) кода
	Alt+кнопка мыши - несколько курсоров ( размножнние курсоров )
	Alt+стрелочка вверх/низ - перемещение выделенного кода
	Shift+ стрелка влево/вправо - выделение кода по букве
	Ctr+ стрелка влево/вправо - выделение кода по строке
	Ctr+Shift - быстрое выделение
	Alt+W - оборачивание кода (нужен плагин)
	Ctr+F - быстрый поиск кода по одному конкретному документу
	Ctr+Shift+F - быстрый поиск кода по всему документу, который есть в VSCode
	
	Вопросы:

33 Урок - Основные организационные моменты
	Памятка:
	Вопросы:

34 Урок - Подготовка к верстке
	Памятка:
	Вопросы:

35 Урок - Верстка сайта
	Памятка:
	Вопросы:

36 Урок - Верстка about us
	Памятка:
	Вопросы:

37 Урок - Реализация секции
	Памятка:
	Вопросы:

38 Урок - Вертска секции
	Памятка:
	Вопросы:

39 Урок - Вертска слайдера
	Памятка:
	Вопросы:

40 Урок - Вертска сдайдера часть 2 
	Памятка:
	Вопросы:		