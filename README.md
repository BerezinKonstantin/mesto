# Mesto

## Обзор

Данный проект является результатом самостоятельной практической работы, выполненной по теме **Базовый JavaScript и работа с браузером** курса _[Яндекс Практикума](https://praktikum.yandex.ru/)_

Сайт представляет из себя интерактивную страницу, куда можно добавлять фотографии, удалять их и ставить лайки. Существует возможность редактировать информацию о текущем пользователе и обновлять его аватар.

## Результат

**[GitHub Pages](https://berezinkonstantin.github.io/mesto/)**

## Используемые технологии

Для верстки сайта использовались:

- Flexbox
- Grid

Для функционала:

- чистый Javascript

Сборка проекта:

- Webpack

## Функционал

- Авторизация пользователя производится через токен
- При нажатии на аватар пользователя всплывает модальное окно для вставки ссылки на аватар.
- При нажатии на кнопку рядом с информацией о пользователе всплывает модальное окно для их редактирования.
- Кнопка "+" вызывает поп-ап для добавление новой карточки.
- При нажатии на фото на карточкее появится поп-ап с полный изображением.
- Реализована возможность поставить лайк карточке, отображение общего кол-ва лайков.
- Реализована возможность удаления карточки, если вы её ранее добавили. На ваших карточках имеется иконка удаления.
- Все формы валидируются, на соответствие URL, нельзя отправить пустые данные и менее 2х символов.

Весь функционал реализован на учебном API, предоставленным Яндексом.
Данные о имеющихся фотографиях получаются через соответствующие запросы к API и хранятся на учебном сервере, за их содержание и корректное отображение разработчик не несёт ответственности, т.к. они добавляются всеми обучающимися.

Код проекта и файловая система оформлены в соответствии с методологией **БЭМ** по **Nested**-схеме

Вы можете посмотреть [результат на GitHub Pages](#результат) или развернуть проект локально.

## Установка проекта

- Скачать или клонировать репозиторий

    git clone https://github.com/BerezinKonstantin/mesto.git

- Установить [Node.js](https://nodejs.org/) в случае его отсутствия.
- Установить зависимости

    npm i

- Запуск в режиме разработки, с хот-релоудом

    npm run dev
