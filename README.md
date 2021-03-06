# Курсовая работа Admire Chart

Репозиторий содержит в себе исходный код проекта курсовой работы по реализации приложения для построения
многоугольной процентной диаграммы.

Проект написан на языке _TypeScript_, с использованием фреймворка _React.js_ и библиотеки компонентов _Material UI_.
Для построения графиков используется нативное браузерное _API_ для работы с `canvas`.

## Запуск проект

С использованием _node.js_ и пакетного менеджера yarn:

`yarn install` - установка необходимых зависимостей.

`yarn dev` - запуск в режиме _dev_ сервера.

Для сборки продуктовой версии приложения:

`yarn install` - установка необходимых зависимостей.

`yarn build` - компиляция проекта в SPA.

Для просмотра скомпилированного приложения необходимо запустить проксирование запросов на директорию собранного проекта (директория `build`).
Например, с использованием программы _http-server_:

`npm install --global http-server` - глобальная установка программы _http-server_.

`http-server build` - запуск сервера для доступа к скомпилированному приложению.
