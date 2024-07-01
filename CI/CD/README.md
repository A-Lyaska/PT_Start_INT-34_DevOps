Запуск и проверка с Docker Compose.

Запуск Docker Compose:

1. В корневой директории вашего проекта выполните команду:

docker-compose up --build

2. Проверка работы сервера с Docker Compose:

Откройте новый терминал и выполните команду curl для проверки конечной точки /healthz:

curl http://localhost:8080/healthz

Вы должны увидеть ответ 200 OK.

Либо откройте браузер и перейдите по адресу http://localhost:8080/healthz. Вы должны увидеть текст 200 OK.