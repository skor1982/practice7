# practice7
Проектная работа 7


Собран образ на основе Ubuntu 20.04 с тестовым приложением DEVOPS-praktikum_Docker.
При сборке указан путь контекста /srv, чтобы иметь возможность копировать оттуда файлы.
Dockerfile указан отдельно.
Для теста создан пользователь www и база www_data. Соединение проходит через bridge.


$ sudo docker images
REPOSITORY       TAG       IMAGE ID       CREATED          SIZE
test_python_db   latest    9516f15573eb   7 minutes ago    185MB
