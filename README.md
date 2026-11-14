# html-module
# 🌐 Модуль HTML: Основы верстки и структура веб-страниц

В этом репозитории собраны мои задания и решения по модулю HTML. Здесь я изучил базовые теги, работу со стилями (CSS), списками, таблицами и формами.

## 📚 Изученные темы
- **Базовые теги:** Заголовки (`h1`-`h6`), параграфы (`p`), контейнеры (`div`), переносы строк (`br`).
- **Ссылки и медиа:** Тег `<a>` (атрибут `href`), тег `<img>` (атрибут `src`).
- **Списки:** Нумерованные (`ol`) и маркированные (`ul`).
- **Таблицы:** Создание таблиц (`table`, `tr`, `td`).
- **Формы:** `<form>`, текстовые поля, `email`, `number`, `date`, `textarea`, `checkbox`, `radio`, `select` (включая `multiple`), кнопки.
- **Стилизация:** Внутренние стили (`<style>`), классы (`.class`), идентификаторы (`#id`), инлайн-стили (`style="..."`).

---

## 💻 Class Work (Практика на занятии)

```html
<!--
HTML - скелет сайта
CSS - стили 

HEAD - подключение стилей и скриптов
BODY - контент сайта (тексты / видео / фото и тд)

h1 ... h6
. - class
# - id
# - якорь или анкор

ТЕГ <a>
АТРИБУТ href - то что прикладывается к тегу
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .elnur{
            color:red;
        }

        #vitali{
            color:green;
        }

        #d1{
            width:300px;
            height:300px;
            background: red;
        }

        td{
            width:300px;
            height:200px;
            border:3px solid black;
        }

        input{
            width:300px;
            height:30px;
            border:3px solid black;
            font-size:22px; 
        }

        textarea{
            width:300px;
            height:200px;
            border:3px solid black;
            font-size:22px; 
        }

        select{
            width:300px;
            height:40px;
        }
    </style>
</head>
<body>
    <h1>Hello Elnur!</h1>
    <h2 class="elnur">Hello Elnur!</h2>
    <h2 id="vitali">Hello Vitali!</h2>

    <p>
        Paragraph ...
    </p>

    <p style="font-size:40px;">Hello from <span style="color:red;">USA</span></p>

    <div id="d1"></div>

    <a href="#">Клики на меня</a>
    <a href="https://google.com">Клики чтобы попасть на Google</a>

    <br>

    <img src="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_16x9.jpg?w=1200"/>

    <br>

    <ul> <!-- unordered list -->
        <li>One</li>
        <li>Two</li>
        <li>Three</li>
    </ul>

    <ol> <!-- ordered list -->
        <li>One</li>
        <li>Two</li>
        <li>Three</li>
    </ol>

    <br>

    <table>
        <tr> <!-- table row -->
            <td>One</td> <!-- table data -->
            <td>Two</td>
        </tr>
        <tr>
            <td>Three</td>
            <td>Four</td>
        </tr>
    </table>

    <br>

    <form>
        <input type="text" placeholder="Enter your name ...">
        <br>
        <input type="email" placeholder="Enter your email ...">
        <br>
        <input type="number" placeholder="Enter your age ...">
        <br>
        <input type="date">
        <br>
        <textarea></textarea>
        <br>
        <input type="checkbox">
        <br>
        <label>Male</label>
        <input type="radio" name="gender">
        <label>Female</label>
        <input type="radio" name="gender">
        <br>
        <select>
            <option>USA</option>
            <option>SPAIN</option>
            <option>Argentina!!!</option>
        </select>
        <br>
        <select multiple>
            <option>USA</option>
            <option>SPAIN</option>
            <option>Argentina!!!</option>
        </select>
        <br>
        <button>CLICK ME!!!</button>
        <br>
        <input type="button" value="CLICK ME 2222">
        <br>
        <input type="submit" value="CLICK ME 2222">
        <br><br><br><br><br><br><br><br>
    </form>
</body>
</html>
```

# 📝 Home Work (Домашние задания)
 
В рамках домашнего задания необходимо сверстать две страницы (форму и макет сайта), используя изученные теги.
 
## Задание 1: Форма (Dynamic Converter)
 
Задача: Создать форму, похожую на панель администратора.
 
https://docs.oracle.com/cd/E21764_01/doc.1111/e10634/img/new_template.gif
 
Что нужно использовать:
Теги <form>, <input> (разных типов), <select>, <textarea>, <button>, а также таблицу или div для выравнивания элементов по колонкам. Обратите внимание на обязательные поля со звездочкой *.
````html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>

        input{
            width: 100px;
            height: 50px;
            border: 4px solid;
            font-size: 22px;
        }
        select{
            width: 100px;
            height: 50px;
        }
        textarea{
            width: 100px;
            height: 50px;
            border: 3px solid black;
        }





    </style>
</head>
<body>
    <h1>Content ID</h1>
    <input type="text" placeholder="your id">
    <br>
    <h1>Type</h1>
    <select>
        <option>adacct - acme acounting departemnt</option>
        <option>frt</option>
    </select>
    <br>
    <h1>Tittle</h1>
    <textarea></textarea>
    <br>
    <h1>Filer</h1>
    <input type="text">
    <select>
        <option>
            sysadmin
        </option>
        <option>
            admin
        </option>
    </select>
    <br>
    <h1>Security group</h1>
    <select>
        <option>
            public
        </option>
        <option>
            privat
        </option>
    </select>
    <br>
    <h2>Template format</h2>
    <label>HTML Conversion Template</label>
    <input type="radio" name="gender">
    <label>Classic HTML Conversion Template</label>
    <input type="radio" name="gender">
    <br>
    <h2>Revesion</h2>
    <input type="age">
    <br>
    <h2>Folder</h2>
    <input type="file" name="browse">
    

</body>
</html>
```

## Задание 2: Макет сайта (Green and Plain)
 
Задача: Сверстать макет блога с шапкой, основной частью, боковой панелью и подвалом.
 
https://blog.hostbillapp.com/wp-content/uploads/2009/11/original.jpg
 
Что нужно использовать:
Семантические теги (например, <header>, <main>, <aside>, <footer>), списки <ul> для меню навигации, теги заголовков и параграфов для текста. Для создания сетки (две колонки) можно использовать display: flex во внутренних стилях или табличную верстку.
```html
<!--
HTML - скелет сайта
CSS - стили 

HEAD - подключение стилей и скриптов
BODY - контент сайта (тексты / видео / фото и тд)

h1 ... h6
. - class
# - id
# - якорь или анкор

ТЕГ <a>
АТРИБУТ href - то что прикладывается к тегу
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        header{
            display: flex;
            padding: 20px 40px;
        }
        main{
            display: flex;
            }
        header{
            background-color: green;
        }
        h1{
            color: aliceblue;
        }
        nav{
            padding: 55px 400px;
            display: flex;
            gap: 10px;
        }
        .main-nav{
            text-decoration: none;
            padding: 55 400px;
            font-size: 14px;
        }
        .wer-h1{
            color: black;
        }
        section{
            max-width: 960px;
            padding: 0px 20px;
        }
        footer{
            background-color: greenyellow;
            text-align: center;
            padding: 20px 0px;
            margin-top: 30px;
            font-size: 12px;
        }
        h2{
            background-color: greenyellow;
            padding: 10px 15px;
            margin-top: 15px;
            margin-bottom: 15px;
            font-size: 16px; 
        }
        h4{
            background-color: greenyellow;
            padding: 10px 15px;
            margin-top: 15px;
            margin-bottom: 15px;
            font-size: 16px;
        }
        ul{
            list-style: none;
            padding: 0px;
            margin: 0px;
        }
        article{
            padding: 30px;
        }
    </style>
</head>
<body>
    <header>
        <div>
            <h1>Green and plain</h1>
            <p>Design by free CSS templates</p>
        </div>
        <nav class="main-nav">
            <a href="#">home</a>
            <a href="#">About</a>
            <a href="#">Products</a>
            <a href="#">Servises</a>
            <a href="#">Contact us</a>
        </nav>  
    </header>
    <main>
        <section>
            <article>
            <h1 class="wer-h1">Welcome to our website</h1>
            <p>posted by freecsstemplates</p>
            <p>
                Green and Plain is a free template 
                <a href="#">from CSS Templates</a> released under a 
                <a href="#">Creativ Commons Attribution 2.5</a> License. You're free 
                to use this template for both commercial or personal use. 
                I only ask that you link back to 
                <a href="#">my site</a> in some way. Enjoy:)
            </p>
            <p>
                <a href="#">Comments</a>
                * <a href="#">Read full post</a>
            </p>
            </article>
            <article>
                <h1 class="wer-h1">Lorem Ipsum Dolor Volutoat</h1>
                <p>Posted by free css templates</p>
                <p>Curabitur tellus. Phasellus tellus turpis, iaculis in, 
                faucibus lobortis, posuere in, lorem. Donec a ante. Donec 
                neque purus, adipiscing id, eleifend a, cursus vel, odio. 
                Vivamus varius justo sit amet leo. Morbi sed libero. 
                Vestibulum blandit augue at mi. Praesent fermentum lectus 
                eget diam. Nam cursus, orci sit amet porttitor iaculis, 
                ipsum massa aliquet nulla, non elementum mi elit a mauris.</p>
                <p>*<a href="#">Magna lacus bibendum mauris</a></p>
                <p>*<a href="#">Velit semper nisi molestie</a></p>   
                <p>*<a href="#">Magna lacus bibendum mauris</a></p> 
                <p>*<a href="#">Velit semper nisi molestie</a></p> 
                <h3><a href="#">Comments (32)</a> * <a href="#">Read full post</a></h3>
            </article>
        </section>
        <aside>
            <h2>Search</h2>
            <input>
            <button>Search</button>
                <h4>Lorem Ipsum</h4>
            <ul>
                <il>Fusce dui neqey fringilla</il>
                <li>Eget tempor eget nonummy</li>
                <li>magna lacus bibendum mauris</li>
                <li>nec metus sed donec</li>
                <li>magna lacus bibendum mauris</li>
                <li>velit tempir eget nonummy</li>
                <li>eget tempor eget nonummy</li>
            </ul>
                <h4>Volutpate depet</h4>
            <ul>
                <li>nec metus sed donec</li>
                <li>magna lacus bibendum mauris</li>
                <li>velit semper nisi molestie</li>
                <li>nec metus sed donec</li>
                <li>magna lacus bibendum mauris</li>
                <li>velit semper nisi molestie</li>
            </ul>
        </aside>
    </main>
    <footer>
        <p>2008. ALL RIGHT Reserved</p>
    </footer>
</body>
</html>
```
