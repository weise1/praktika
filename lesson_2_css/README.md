## Основи Web UI розробки 2023
Завдання №1
1/1 point (graded)
Опис завдання:
Відформатувати блоки тексту як в прикладі

Приклад (https://courses.prometheus.org.ua/assets/courseware/v1/f94993a53797ff5355b8cb8dd5b4b102/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task1.png)

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Вивчаємо CSS</title>
    <style>
        #select_by_id{
            font-weight: bold;
        }

        .select_by_class{
            text-decoration: underline;
        }

        p {
            text-align: right;
        }
    </style>
</head>

<body>
<p id="select_by_id">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

<p class="select_by_class">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

<p>HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>
</body>
</html>
```
Завдання №2
1/1 point (graded)
Опис завдання:
Відформатувати блоки тексту як в прикладі

Приклад(https://courses.prometheus.org.ua/assets/courseware/v1/23b521c3abb45fb239c0ab85784c92b1/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task2.png)

```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Вивчаємо CSS</title>
    <style>
        body {
            font-family: Arial;
            font-size: 16px;
            line-height: 1.2em;
        }
        .paragraf1 {
            color: red;
            font-weight: bold;

        }
        .paragraf2 {
            border-width: 2px;
            border-style: solid;
            border-color: blue;
            background-color: yellow;
            text-align: right;
            color: green;

        }
        .paragraf3 {
            text-decoration: underline;
            text-transform: uppercase;
        }
    </style>
</head>

<body>
<p class="paragraf1">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

<p class="paragraf2">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>

<p class="paragraf3">HTML - стандартна мова розмітки веб-сторінок в Інтернеті. Більшість веб-сторінок створюються за допомогою мови HTML. Документ HTML оброблюється браузером та відтворюється на екрані у звичному для людини вигляді.</p>
</body>
</html>
```
Завдання №3
1/1 point (graded)
Опис завдання:
Створити горизонтальне меню. Параметр float: left або float: right не використовувати.

Зразок
(https://courses.prometheus.org.ua/assets/courseware/v1/2177df10376980a9980585a59235e891/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task3.png)


```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <title>Вивчаємо CSS</title>
        <style>
            body{
                padding: 30px;
            }
            nav {
                background: -webkit-linear-gradient(red, blue); /* For Safari 5.1 to 6.0 */
                background: -o-linear-gradient(red, blue); /* For Opera 11.1 to 12.0 */
                background: -moz-linear-gradient(red, blue); /* For Firefox 3.6 to 15 */
                background: linear-gradient(red, blue); /* Standard syntax (must be last) */
                display: inline-block;
            }
            ul, li{
                margin: 0;
                padding: 0;
            }
            a{
                color: white;
                font-weight: bold;
            }
            li {
                display: inline-block;
                list-style-type: none;
                padding: 10px;
                border: 1px solid white;
                
            }
        </style>
    </head>

    <body>
        <nav>
            <ul>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
                <li><a href="#">Текст</a></li>
            </ul>
        </nav>
    </body>
</html>
```
Завдання №4
1/1 point (graded)
Опис завдання:
Створити горизонтальне меню, яке реагує на наведення курсору. Колір тексту повинен змінюватись на червоний (red), а також повинно з'являтися підкреслення тексту.

Зразок
(https://courses.prometheus.org.ua/assets/courseware/v1/11615d550205310e06bf53efdf7b2b23/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task4.png)


```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Вивчаємо CSS</title>
    <style>
        body{
            padding: 30px;
            color: white;
        }
        nav {
            background: -webkit-linear-gradient(red, blue); /* For Safari 5.1 to 6.0 */
            background: -o-linear-gradient(red, blue); /* For Opera 11.1 to 12.0 */
            background: -moz-linear-gradient(red, blue); /* For Firefox 3.6 to 15 */
            background: linear-gradient(red, blue); /* Standard syntax (must be last) */
            display: inline-block;
        }
        ul, li{
            margin: 0;
            padding: 0;
        }
        li {
            list-style-type: none;
            padding: 10px;
            border: 1px solid white;
            display: inline-block;
        }
        a {
            color: white;
            text-decoration: none;
        }

        li:hover a {
            color: red;
            text-decoration: underline;
        }
    </style>
</head>

<body>
<nav>
    <ul>
        <li><a href="#">Текст</a></li>
        <li><a href="#">Текст</a></li>
        <li><a href="#">Текст</a></li>
        <li><a href="#">Текст</a></li>
        <li><a href="#">Текст</a></li>
    </ul>
</nav>
</body>
</html>
```
ЗЗавдання №5
1/1 point (graded)
Опис завдання:
Розмістити на сторінці 5 блоків так, щоб при зміні ширини браузера вони теж змінювати ширину. Відповідь ховається в задачі про меню. Параметр float: left або float: right не використовувати.

Зразок
Початковий вигляд
(https://courses.prometheus.org.ua/assets/courseware/v1/189a4eadd86a135a318b78085304dcde/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task5_1.png)
Вигляд після масштабування:
(https://courses.prometheus.org.ua/assets/courseware/v1/d5a061c446a85adb460909c00de12585/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task5_2.png)
<b>Рішення:</b>
```<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>Вивчаємо CSS</title>
    <style>
        div {
            border: 2px dashed blue;
            background-color: yellow;
            height: 100px;
            box-sizing:border-box;
            display: inline-block;
            width: 20%;
        }
    </style>
</head>

<body>
<div></div><div></div><div></div><div></div><div></div>
</body>
</html>
```
Завдання №6
1/1 point (graded)
Опис завдання:
Додати 3 вкладених списка з різними позначками перед <li> елементом. Як в прикладі. Дотримуйтесь послідовності.
Приклад:
https://courses.prometheus.org.ua/assets/courseware/v1/84382361770d77f310811a44abf9eeaa/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task6.png

```<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <title>Вивчаємо CSS</title>
        <style>
            .list1 li {
                list-style-type: disc;
            }
            .list2 li {
                list-style-type: circle;
            }
            .list3 li {
                list-style-type: square;
            }
        </style>
    </head>

    <body>
    <ol>
        <li>Заголовок 1
            <ul class="list1">
                <li>Текст</li>
                <li>Текст</li>
                <li>Текст</li>
            </ul>
        </li>
        <li>Заголовок 2
            <ul class="list2">
                <li>Текст</li>
                <li>Текст</li>
                <li>Текст</li>
            </ul>
        </li>
        <li>Заголовок 3
            <ul class="list3">
                <li>Текст</li>
                <li>Текст</li>
                <li>Текст</li>
            </ul>
        </li>
    </ol>
    </body>
</html>
```
Завдання №7
1/1 point (graded)
Опис завдання:
Розмістіть блоки як на малюнку, використовуючи відносне та абсолютне позиціонування. Синій блок прив'язати до правого нижнього кута.

*Підказка: для прив`язки використовуйте параметри bottom та right

Приклад(https://courses.prometheus.org.ua/assets/courseware/v1/a9fb80358f9f55353ecd3c85441a6c4d/asset-v1:LITS+114+2022_T2+type@asset+block/Learn_CSS_Task7.png)
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <title>Вивчаємо CSS</title>
        <style>
            .parent {
                width: 200px;
                height: 200px;
                background-color: yellow;
                margin: 20px auto;
                position: relative;
            }

            .child {
                width: 50px;
                height: 50px;
                background-color: blue;
                position: absolute;
                bottom: 0px;
                right: 0px;
            }
        </style>
    </head>

    <body>
    <div class="parent">
        <div class="child"></div>
    </div>
    </body>
</html>
```



-------------------------------------------------------------------------------------------------------------------------------

