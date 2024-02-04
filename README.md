# Git-user-finder

---

## Описание проекта

Функционал приложения:

-   Поиск пользователей,
-   Сортировка по количеству репозиториев: по возрастанию/убыванию,
-   Просмотр результатов поиска с разбиением на страницы,
-   Просмотр информации профиля пользователя,

Особенности проекта

-   Обработка ошибок сервера,
-   Используется лоадер при загрузке данных пользователей,
-   Отзывчивый интерфейс. При отправке запросов/нажатия на кнопки, пользователь видит что происходят какие либо действия, а не просто ждет.

---

## Ссылка на deploy проекта

https://artcode-x.github.io/git-user-finder/

## Стек технологий используемый при разработке проекта

-   React
-   Redux (Redux Toolkit / CreateSlice)
-   Styled Components
-   React Router
-   Axios
-   Линтеры

## Назначение папок и файлов проекта

- **/components** - Компоненты используемые в проекте
- **/pages** - Страницы приложения  
- **/store** - Управление состояниями приложения
- **/api** - Запросы к API (бэкэнду)  
- **/app** - Главный компонент приложения

---

## Примечания по локальному запуску проекта для разработки

Для клонирования репозитория выполните команду:

```
git clone https://github.com/Artcode-x/git-user-finder
```

Перейти в папку проекта и установить зависимости перед запуском:

```
npm install
```

Запуск проекта:

```
npm run start
```

Запуск тестов:

```
npm test
```

Проект будет запущен по адресу: http://localhost:3000

## Backend / документация

- Документация: https://developer.github.com/v3/search/#search-users
- Данные по пользователям берем с https://api.github.com/search/users?q={userName}
