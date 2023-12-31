# Вводный Урок: История Веба и Основы HTML

История Веба

Тим Бернерс-Ли (Изобретатель Всемирной паутины): Британский ученый, который в 1989 году в ЦЕРНе (Европейская организация по ядерным исследованиям) предложил концепцию гипертекстовой системы, что стало основой для создания Всемирной паутины.

ЦЕРН (Ведущая лаборатория по физике частиц): Европейская организация, занимающаяся исследованиями в области физики высоких энергий. Именно здесь в 1989-1990 годах Тим Бернерс-Ли разработал первый веб-браузер и веб-сервер.

Развитие Веб-технологий: После изобретения веба последовало быстрое развитие технологий. HTML, CSS и JavaScript стали ключевыми инструментами для создания веб-страниц и веб-приложений.

История HTML, CSS и JavaScript
HTML (HyperText Markup Language): Язык разметки, разработанный в начале 90-х годов, который определяет структуру и содержимое веб-страниц.

CSS (Cascading Style Sheets): Стилевой язык, представленный в 1996 году, который используется для оформления внешнего вида HTML-документов.

JavaScript: Язык программирования, впервые представленный в 1995 году Бренданом Эйхом (Американский программист и создатель JavaScript), стал ключевым элементом для добавления интерактивности к веб-страницам.

# Основы HTML
Структура HTML-документа:

`<!DOCTYPE html>`: Объявление, указывающее браузеру версию HTML. 
`<html>`: Корневой элемент, который обрамляет весь HTML-документ.
`<head>`: Содержит метаинформацию и заголовок страницы.
`<body>`: Основное содержимое веб-страницы.
Основные Элементы HTML:

`<h1>, <h2>, ..., <h6>`: Заголовки различных уровней.
`<p></p>`: Параграф или абзац текста.
`<a href="...">`: Ссылка на другую веб-страницу.
`<img src="..." alt="...">`: Вставка изображения.
`<ul>, <ol>, <li>`: Списки (ненумерованные и нумерованные).
`<div>`: Разделительный контейнер для группировки и форматирования блоков содержимого. Очень мощный инструмент для структурирования веб-страницы и управления макетом с помощью CSS.

Что такое HTML-теги?

HTML-теги - это основные строительные блоки HTML. Они используются для создания и форматирования веб-страниц.
Теги обозначаются угловыми скобками, например, `<tagname>`. Каждый тег имеет свое назначение и функцию.
Большинство тегов имеют закрывающие пары, например` <p>...</p>`, но есть и самозакрывающиеся теги, такие как` <img src="..." alt="...">`.
Типы Тегов:

Структурные теги: Определяют структуру и разделы веб-страницы, например, `<html>, <head>, <body>`.
Теги контента: Используются для добавления текста, изображений, ссылок и т.д., например, `<p>, <img>, <a>`.

Важность Тегов в HTML:
Теги определяют, как браузер должен интерпретировать и отображать содержимое веб-страницы.
Правильное использование тегов обеспечивает лучшую доступность и совместимость с различными устройствами и браузерами.

Блочные и Строчные Теги в HTML


В HTML теги делятся на два основных типа: блочные и строчные. Понимание различий между этими типами тегов важно для правильного построения структуры веб-страницы.
Блочные Теги: Блочные теги создают "блоки" контента, которые автоматически начинаются с новой строки и занимают всю доступную ширину.
Особенности: Занимают всю ширину контейнера, в котором находятся.
Можно управлять шириной и высотой.
Часто используются для создания крупных структурных элементов страницы.
Примеры:
`<div>`: Универсальный контейнер для группировки элементов.
`<p>`: Параграф текста.
`<h1>, <h2>, ..., <h6>`: Заголовки различных уровней.
`<ul>, <ol>`: Ненумерованные и нумерованные списки.
`<li>`: Элемент списка.
`<header>, <footer>, <section>, <article>`: Семантические элементы для структурирования содержимого.
Блочные теги не могут быть использованы внутри строчных тегов.
Строчные Теги:

Описание: Строчные теги предназначены для форматирования отдельных частей текста или добавления небольших элементов, не прерывая поток документа.
Особенности:
Не начинаются с новой строки и занимают только столько места, сколько необходимо для содержимого.
Не возможно управлять шириной и высотой.
Используются для мелких элементов, таких как ссылки, выделение текста, изображения.
Примеры:
`<a>`: Ссылка.
`<span>`: Универсальный строчный контейнер.
`<img>`: Изображение.
`<strong>, <em>`: Выделение текста с помощью жирного или курсивного начертания.
`<br>`: Перенос строки.
`<small>, <big>`: Изменение размера текста.
Важность Различия между Блочными и Строчными Тегами
Понимание различий между блочными и строчными тегами помогает создавать более организованные и структурированные веб-страницы. Блочные элементы часто используются для создания основного макета страницы, в то время как строчные элементы применяются для мелкой стилизации и выделения отдельных частей контента.
Строчные теги могут использоваться внутри блочных тегов.

Эти знания помогут вам правильно размещать и стилизовать элементы на веб-странице, создавая чистую, доступную и эстетически приятную структуру контента.
# Использовать на практике пройденный материал
## ЗАДАЧИ 
 #### ⚠️Важно ни в коем случае не копипастить (копировать чужой код copy-paste ) код обязательно прописывать каждую строчку самому, можно гуглить и искать решение но копипастить строго запрешено
 
Для первого урока по HTML, вот несколько практических заданий, которые помогут ученикам закрепить полученные знания:
### 🏆Задание 1: Создание Базовой HTML-Страницы
1.1 Создайте простую HTML-страницу.
Начните с объявления типа документа `<!DOCTYPE html>`.
Добавьте корневой элемент <html> с дочерними элементами `<head> и <body>`.
И в `<head>`, не забудьте указать заголовок страницы с помощью `<title>`.

 1.2 Добавьте контент в `<body>`:
`<h1>` задает заголовок первого уровня, который обычно используется для наиболее важного заголовка на странице.
Первый `<p>` содержит вводный текст, раскрывающий тему урока.
Во втором `<p>`, тег <strong> используется для выделения слова "фундаментом", делая его более заметным и подчеркивая его важность.
Этот код создает базовую структуру HTML-страницы с заголовком и двумя абзацами текста.

🔗[Ссылка на задание 1.1](http://greatcode.ru/lesson_1.1.1.html). </br>
🔗[Ссылка на задание 1.2](http://greatcode.ru/lesson_1.1.2.html). </br>
🛑 во втором задании есть линии с этого момента начинаем пользовать БРАУЗЕРОМ вбиваем в поиск `[линия html]` 

### 🏆Задание 2: Работа со Списками и Ссылками
2.1 Создайте нумерованный список (`<ol>`) и ненумерованный список (`<ul>`):

В каждом списке должно быть не менее пяти элементов (`<li>`). </br>
🔗[Описание тегов для работы со списком ](https://doka.guide/html/li/). </br>
🔗[Ссылка на задание 2.1](https://greatcode.ru/lesson_1.2.1.html). </br>
Дальше придется чуть поднапрячься </br>
🔗[Ссылка на задание 2.2](https://greatcode.ru/lesson_1.2.2.html). </br>
🛑 в этом задании есть упорядоченный список с римскими цифрами и список который начинается с 10 буквы всю информацию можете найти в книге [`htmlbook.ru` в поиске `ol и ul`] </br>
🔗[Ссылка на задание 2.3](https://greatcode.ru/lesson_1.2.3.html). </br>

В одном из элементов списков используйте гиперссылку (`<a href="#">`), ведущую на любой образовательный ресурс.

### 🏆Задание 3: Эксперименты с Тегами
3.1 Используйте различные заголовки (`<h2>, <h3>`, и т.д.):

Создайте разделы на вашей странице с использованием различных уровней заголовков.
Обратите внимание на изменения в размере и важности заголовков.
🔗[Описание тегов для работы с заголовками ](https://doka.guide/html/h1-h6/).
Форматирование текста:

Экспериментируйте с тегами `<em>, <strong>, <b>, и <i>` для изменения стиля текста в абзацах.
Попробуйте использовать тег `<br>` для переноса строки в абзаце. </br>
Если с этим  возникают трудности то это опустим для следующего урока

🔗[Ссылка на задание 3.1](https://greatcode.ru/lesson_1.3.1.html). </br>
⚠️ Очень важно не копировать код, а прописывать его самим и не использовать значения в примерах, важна индивидульность каждого задания

🛑 По этим тегам стараемся искать документацию сами в dokaGuide или Htmlbook.ru
