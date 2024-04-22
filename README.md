# Task_2

## Сборка из файла Dockerfile и запуск образа

Для сборки контейнера из Dockerfile необходимо:
1. Перейти в каталог Task_2 при помощи команды: cd Task_2
2. Произвести сборку контейнера в текущем каталоге, используя команду: docker build . --tag=my-server, где my-server - это имя сервера.

Для запуска образа необходимо использовать команду: docker run -d -p 8000:80 --name=name_server my-server
