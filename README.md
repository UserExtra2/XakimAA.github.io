# Задание 1ого модуля #
Задание выполнено в рамках "Школы разработки".
Веб-приложение можно просмотреть по [ссылке](https://xakimaa.github.io/)

## Что можно сделать с помощью данного веб-приложения? ##
1. На главной странице приложения просмотреть список счетов (накладных).
2. Выполнить создание, редактирование и удаление накладных.
3. Отфильтровать данные по значению выбранного поля (с использованием операции “равно”).
4. Для списка на главной странице приложения поддерживается полнотекстовый поиск по всем полям.
5. Для списка на главной странице приложения подерживаеться сортировка по одному полю в трех режимах: “по возрастанию”, “по убыванию”, “без сортировки”.
Фильтрация, сортировка и поиск для списка на главной странице приложения работают совместно, т.е. в запросе должно учитываться всё, что выбрал пользователь.

## Что было использовано? ##
* Для получения списка накладных должны выполняются запросы к серверу на основе REST API.
* В качестве сервера для публикации REST API необходимо использовать JSON Server.
* Сервер развернут на Heroku.
* Для выполнения запросов к серверу из приложения используется AJAX (средствами jQuery)

## Тестирование сетевого взаимодействия и серверного API ##
Было выполнено тестирование с помощью инструментов postman и fiddler.
Результаты тестирования находятся в папке task_2