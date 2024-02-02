# Склады и товары


## Документация по проекту

Для запуска проекта необходимо выполнить команды

docker build -t my_django:v1 -f django_dockerfile .

docker run -p 8000:8000 my_django:v1

после запуска сервера, проект будет доступен по адресу: http://localhost:8000/api/v1/
