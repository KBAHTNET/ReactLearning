# Работа с проектом
1. Установить необходимые пакеты
```
npm i
```
2. 
    1. Для быстрого dev-сервера:
    ```
    npm start
    ```
    2. Для сборки проекта
    ```
    npm build
    ```
___

# Админ панель героев

Пример SPA, реализованном на React+Redux.

Использование функциональных компонентов в проекте.

При написании данного веб-приложения было использовано:
- useState - хук, который позволяет добавлять состояние в функциональные компоненты React. Он позволяет сохранять и изменять значения переменных внутри компонента и вызывать перерендеринг при изменении значения.
- useEffect - хук, который позволяет выполнять эффекты, зависимые от состояния компонента, например, обращаться к API или изменять DOM
- useMemo - хук, который позволяет кэшировать результат выполнения функции и повторно использовать его при следующих вызовах
- useDispatch - хук из библиотеки Redux, который позволяет получить функцию dispatch, который используется для отправки экшенов в хранилище (store) Redux.
- useSelector - хук из библиотеки Redux, который используется для получения данных (состояния) из хранилища (store) Redux внутри функциональных компонентов.
- созданы кастомные хуки
- работа с хранилищем состояний (store)


___

![alt text](https://github.com/KBAHTNET/ReactLearning/blob/main/public/screen.png)