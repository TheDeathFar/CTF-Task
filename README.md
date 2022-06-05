# Задание №6. Разворачивание сервиса в k8s.

## Описание проделанной работы.

1) Подготовлен кластер в Yandex Cloud.
2) Репозиторий, взятый за основу - https://github.com/CTFd/CTFd.
3) Установлены базы данных mariadb и redis. Также созданы для них yaml-файлы для переопределения переменных.
4) Развернут nginx-ingress-controller из helm пакета.
5) Написан helm-чарт для CTFd, который включает в себя Deployment, Service и Ingress.

![pods](/img/pods.jpg "Поднятые поды в кластере.")

![sample](/img/sample.jpg "Пример работы сервиса.")