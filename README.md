Тестовый проект Web приложение с рандомными метриками,экпортером,сборщиком и визуализатором.
Сбор метрик Prometheus
Визуализация метрик Grafana
Все завернуто в Docker контейнеры.

Запуск всех контейнеров в нужной последовательности - docker-compose up -d
Останавливаем все контейнеры и удаляем собранные образы - docker-compose down -v --rmi all
