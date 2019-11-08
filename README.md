Настройка react app

 1. Развернуть приложение с помощью CRA (по желанию)
 2. Настроить кастомный webpack + babel проект (+2 балла)
 3. Заставить работать TypeScript через babel (+1 бал)
 4. Написать хелло ворлд (todo app или любое другое), сделать базовую верстку вашего приложения, поработать с JSX (+2 бал)


https://ru.reactjs.org/tutorial/tutorial.html#what-are-we-building

Документация по webpack
https://webpack.js.org/guides/getting-started/

Документация по babel
https://babeljs.io/docs/en/

Typescript preset https://babeljs.io/docs/en/babel-preset-typescript

Можете взять за основу простое todo приложение

https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/todos

npx create-react-app 08-cra

npm start

npm install babel-cli@6 babel-preset-react-app@3

npx babel --watch src --out-dir . --presets react-app/prod