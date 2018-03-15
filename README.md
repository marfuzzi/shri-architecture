# shri-architecture
Задание по архитектуре для ШРИ-2018

## Постановка задачи
Вам предлагается реализовать 2 архитектурных подхода - MVP и Flux - в формате простого фреймворка. Ваш фреймворк должен уметь обрабатывать действия пользователя и предоставлять API для связи с бэкэндом

## Требуемая реализация
Вам предлагается 2 файла - `index.html` и `sendToServer.js`.
В `index.html` вы найдете простую форму: инпут для ввода текста, кнопку "отправить на сервер" и лейбл.
В `sendToServer.js` находится фейковый метод отправки данных на сервер. После "успешной отправки" метод вызывает событие `dataIsSent`.

Вам предлагается написать MVP и Flux реализацию фреймворка, который бы осуществлял отправку данных на сервер по нажатию на кнопку, а после успешной отправки писал в лейбле "Сервер принял данные <текст из инпута>".
Способ переключения между "фреймворками" выберите сами.
Каждый этап (передача данных и/или управления между элементами архитектуры) должен логироваться в консоль.

**Использование фреймворков и библиотек, в том числе jQuery, запрещено.**
Реализовывать виртуальный DOM для Flux-архитектуры не нужно. Изменять API `sendToServer` - можно (при сохранении "функциональности").


## Минимальное решение
- Реализация 2 фреймворков с логированием в консоль

## Оптимальное решение
- Сделать логирование на экран

## Дополнительное задание
- Реализовать другие архитектурные подходы (MVC, MVVM)

## Сроки и сдача
Домашнее задание сдается до 1 апреля 2018. В соответствующий тикет приложите ссылку на репозиторий или решение в архиве и ссылку на работающее приложение.
