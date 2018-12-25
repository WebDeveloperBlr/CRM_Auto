# AutoCRM

Курсовой проект на Angular 6, Node.js, MySql на тему Автоматизированное место работника АЗС
(АРМ сотрудника АЗС). Старый минимальный курсач, он умеет показывать
информацию, добавлять информацию. Никаких нормальных моделей
тут нет, все сделанно давно и наспех, никаких оптимизаций,
но они тут и не нужны. Главное тут - это относительно лекий старт
проекта: автоматическое создание базы и ее запуск вместе с сервером, 
а также готовая пояснительная записка.

## Запуск проекта

Для корректного запуска вам понадобятся:

- [Nodejs](https://nodejs.org/);

- Docker [Docker for windows](https://docs.docker.com/docker-for-windows/install/);

- Angular 6 (или выше): открываем коммандную строку и набираем `npm install -g @angular/cli`.

### Запуск фронтенда

- Через командную строку в корне проекта вводим `npm i`.
- Далее там же вводим `ng serve -o`
 
Должен сбилдиться проект и автоматически открыться в браузере.

### Запуск бэкенда

- Заходим в папку web-service и открываем там командную строку;
- Вводим `docker-compose up`;
 
Должены сбилдиться контейнеры и запуститься. В консоли должно 
появиться сообщение, что сервер запущен и база подключена.

Если все так как нужно, то проект запущен!

## Примечание

У вас должны быть свободные порты 8080 и 3306