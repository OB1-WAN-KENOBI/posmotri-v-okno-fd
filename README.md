[ -RU] (#Проект "Посмотри в окно")
[ -EN] (#Project "Look Out the Window")



# Проект "Посмотри в окно"

## Описание
"Посмотри в окно" — это учебный веб-проект, выполненный в рамках второго курса Яндекс.Практикума. Приложение позволяет искать и просматривать видео по заданному городу и времени суток (утро, день, ночь). Моя основная задача заключалась в создании верстки (HTML и CSS), включая адаптивный дизайн, стилизацию и анимации. Логика на JavaScript была предоставлена Яндекс.Практикумом как заготовка для интеграции с API.

## Основные функции
- **Поиск видео**: Ввод города и выбор времени суток через форму с чекбоксами.
- **Отображение контента**: Видео воспроизводится в плеере, карточки с миниатюрами и описанием отображаются в списке.
- **Интерактивность**: Анимация свечения активной карточки, эффекты при наведении и клике, кастомный скроллбар.
- **Пагинация**: Кнопка "Показать еще" для загрузки дополнительных видео.
- **Обработка ошибок**: Сообщение при отсутствии видео или проблемах с загрузкой.

## Технологии
- **HTML5**: Семантическая разметка с использованием `<template>` для динамических элементов.
- **CSS3**: Flexbox, Grid, кастомные анимации (`@keyframes`), псевдоэлементы, стилизация форм и скроллбара.
- **JavaScript**: Предоставленная заготовка для работы с API, обработки событий и динамического контента.
- **API**: Интеграция с сервером `https://v-content.practicum-team.ru` (реализована в заготовке).
- **Шрифты**: Подключены Oswald и Fira Sans Condensed.

## Особенности верстки
- **Темная тема**: Фон `#1b1919`, белый текст, акценты в сером (`#545050`) и розовом (`#e07ae9`).
- **Анимация свечения**: Эффект `glowingAsh` для подсветки текущей карточки.
- **Кастомные элементы**: Стилизованные чекбоксы с псевдоэлементами, кнопки с `hover/active/focus` состояниями.
- **Сетка**: Использование Grid для компоновки основного контента.

## Установка и запуск
1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/OB1-WAN-KENOBI/posmotri-v-okno-fd.git
   или открыть по ссылке https://ob1-wan-kenobi.github.io/posmotri-v-okno-fd/
   ```
2. Откройте `index.html` в браузере через локальный сервер (например, с помощью Live Server в VS Code).
3. Для работы с видео требуется подключение к API Яндекс.Практикума.

## Роль в проекте
- **Моя работа**: Разработка верстки (HTML и CSS), стилизация интерфейса, анимации и обеспечение визуальной части проекта.
- **Предоставлено Яндекс.Практикумом**: JavaScript-код для обработки форм, запросов к API, пагинации и переключения видео.

## Планы по улучшению
- Доработать адаптивность для мобильных устройств.
- Попробовать самостоятельно реализовать часть JavaScript-логики.
- Добавить локализацию интерфейса.

# Project "Look Out the Window"

## Description
"Look Out the Window" is an educational web project developed as part of the second course at Yandex Practicum. The application allows users to search and view videos based on a specified city and time of day (morning, afternoon, night). My main task was to create the layout (HTML and CSS), including responsive design, styling, and animations. The JavaScript logic was provided by Yandex Practicum as a template for API integration.

## Main Features
- **Video Search**: Enter a city and select a time of day using a checkbox form.
- **Content Display**: Videos are played in a player, and thumbnails with descriptions are displayed in a list.
- **Interactivity**: Glowing animation for the active card, hover and click effects, custom scrollbar.
- **Pagination**: "Show More" button for loading additional videos.
- **Error Handling**: Message displayed when no videos are found or there are loading issues.

## Technologies
- **HTML5**: Semantic markup using `<template>` for dynamic elements.
- **CSS3**: Flexbox, Grid, custom animations (`@keyframes`), pseudo-elements, form styling, and custom scrollbar.
- **JavaScript**: Provided template for API interactions, event handling, and dynamic content.
- **API**: Integration with `https://v-content.practicum-team.ru` (implemented in the provided template).
- **Fonts**: Oswald and Fira Sans Condensed.

## Layout Features
- **Dark Theme**: Background `#1b1919`, white text, gray (`#545050`) and pink (`#e07ae9`) accents.
- **Glowing Animation**: `glowingAsh` effect for highlighting the active card.
- **Custom Elements**: Styled checkboxes with pseudo-elements, buttons with `hover/active/focus` states.
- **Grid Layout**: Used for structuring the main content.

## Installation & Launch
1. Clone the repository:
   ```bash
   git clone https://github.com/OB1-WAN-KENOBI/posmotri-v-okno-fd.git
   or open link https://ob1-wan-kenobi.github.io/posmotri-v-okno-fd/
   ```
2. Open `index.html` in a browser using a local server (e.g., Live Server in VS Code).
3. A connection to Yandex Practicum's API is required for video functionality.

## Role in the Project
- **My Work**: Developing the layout (HTML and CSS), styling the interface, animations, and ensuring the visual design of the project.
- **Provided by Yandex Practicum**: JavaScript code for handling forms, API requests, pagination, and video switching.

## Future Improvements
- Enhance mobile responsiveness.
- Try implementing some JavaScript logic independently.
- Add localization support for the interface.

