# Лабораторна робота №2 з CSS — варіант 5

Автор: Максим Гінчак. Основа проєкту — [лабораторна робота №1 з HTML](https://github.com/MaksHinchak/html_lab_1_hinchak). Тематика сайту: віртуальний магазин комп’ютерних аксесуарів ByteMarket.

## Запуск

Відкрийте цю папку в PyCharm, а `index.html` — через **Open in Browser**. Сервер, JavaScript і встановлення пакетів не потрібні. Меню веде до всіх чотирьох сторінок.

## Файли

- `index.html` — сторінка автора;
- `company.html` — відомості про компанію, каталог і форма;
- `news.html` — новини;
- `css-demo.html` — видимі приклади вимог варіанта 5;
- `assets/css/styles.css` — спільна зовнішня таблиця стилів;
- `assets/images/graphics-card.jpg` — локальне зображення.

## Відповідність варіанту 5

| Вимога | Приклади в CSS / HTML |
|---|---|
| Теги, класи, нащадки, сусіди | `body`, `.news`, `.site-header h1`, `.content-section + .content-section` |
| Атрибути | `img[alt]`, `a[href="company.html"]`, `article[class~="story"]` |
| Псевдокласи | `:first-child`, `:enabled`, `:last-child`, `:last-of-type`, `:lang(uk)`, `:empty` |
| Псевдоелементи | `::first-line`, `::first-letter` |
| Пріоритет | `!important` у позначці новини |
| Поля, відступи, рамки | Основні сторінки й блок «Поля та рамки» на `css-demo.html` |
| Відображення та позиціювання | `inline`, `inline-table`, `table-header-group`, `table-footer-group`, `static`, `fixed`, `float`, `clear` |
| Розміри, висота рядка, вирівнювання, видимість | Навчальні класи в `styles.css`, приклади в `css-demo.html` |
| Колір і фон | `color`, `background-color`, `background-image`, `background-attachment`, `background-position` |

У методичці наведено `display: compact` і `display: run-in`. Вони застаріли та не підтримуються сучасним Chrome. У CSS вони записані разом із робочим `display: inline`, щоб приклади залишалися читабельними. Форма з першої лабораторної демонстраційна: вона показує поля, але не надсилає дані на сервер.
