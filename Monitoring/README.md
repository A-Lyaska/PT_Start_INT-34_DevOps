# Инструкция по запуску

1. В корневой директории вашего проекта выполните команду:

    ```docker-compose up --build```

2. Prometheus:
- Откройте браузер и перейдите по адресу http://localhost:9090.
- В интерфейсе Prometheus перейдите на вкладку "Status", затем в "Targets" (http://localhost:9090/targets). Там будет виден таргет 'https://ptsecurity.com' и его статус.

3. Blackbox Exporter:
- Откройте браузер и перейдите по адресу http://localhost:9115/metrics.
- Видим, что метрики доступны и включают данные о проверке доступности ptsecurity.com.