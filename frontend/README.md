# Проект: Место

### Обзор
* Описание
* Инструкция

## Описание
Проект представляет из себя одностраничный сайт.

Страница представляет собой профиль пользователя:
* Есть аватарка пользователя, 
* Его имя и информация о себе, 
* ряд фотографий выложенных пользователями.

В процессе разработки сайта использовались технологии flexbox, grid и медиазапросы,
чтобы сайт удовлетворял требованиям приведённым в макете,
а также достойно выглядел при разрешениях экрана не указанных в макете.
Также использованы функции на JS для создания различных интерактивностей на странице.

Сайт собран при помощи React, по большей части применялся функциональный подход.
Для выполнения интерактивностей используются запросы на сервер для загрузки
профиля, фотографий, удаления и загрузки новых фотографий, а также запросы
на редактирование профиля.

Также производится проверка по контексту - проверка владельца фотографии,
это сделано для того, чтобы не было возможности удалить чужие фотографии.

## Инструкция
Все стили блоков и элементов импортируются в index.css, который в свою очередь подгружается 
через index.js затем при обэъединении всех файлов рендерится страница сайта с использованием React.
Соответствующие свойства блоков и элементов указаны в папке blocks и вложенных в них папках.
Используемые компоненты сложены в папку components.
Файлы отвечающие за используемые загружаемые шрифты вложены в папку vendor.
Используемые картинки загружаются автоматически входе на сайт.
Используемые иконки находятся в папке images.


## Ссылка для просмотра сайта
https://danitep.github.io/react-mesto-auth/