## Запуск проекта в Docker
- `Установить докер docker.com`
- `Установть docker-compose`
- `Скачать структуру и файлы конфигурации с `
- `Настроить переменные окружения в файле .env`
- `Указать нужные порты в docker-compose.yml`
- `Выполнить docker-compose up --build. При дальнейшем использовании: docker-compose up -d`
- `Для остановки контейнеров docker-compose down`
- `Для запуска работы очереди queue, необходимо: docker-compose exec web echo "php artisan queue:work --queue=email,default --daemon &"`
