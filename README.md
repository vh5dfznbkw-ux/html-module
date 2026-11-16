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

Выполнено: https://github.com/vh5dfznbkw-ux/html-module/blob/main/dd.html

## Задание 2: Макет сайта (Green and Plain)
 
Задача: Сверстать макет блога с шапкой, основной частью, боковой панелью и подвалом.
 
https://blog.hostbillapp.com/wp-content/uploads/2009/11/original.jpg

Выполнено: https://github.com/vh5dfznbkw-ux/html-module/blob/main/home.html#L1
