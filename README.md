# Kittygram

### Используемые технологии

![python version](https://img.shields.io/badge/Python-3.11-green)
![django version](https://img.shields.io/badge/Django-3.2-green)
![django_rest_framework version](https://img.shields.io/badge/DjangoRestFramework-3.12-green)
![djoser version](https://img.shields.io/badge/Djoser-2.1-green)
![postgresql_version](https://img.shields.io/badge/PostgreSQL-13.10-green)
![docker_version](https://img.shields.io/badge/Docker-25.0-green)
![docker_compose_version](https://img.shields.io/badge/DockerCompose-2.23.0-green)

----

## Описание
Проект Kittygram — это социальная сеть для любителей котов, где 
пользователи могут создавать профили для своих питомцев, загружать 
их фотографии и делиться достижениями. Достижения могут включать в себя 
различные награды, полученные на выставках, участие в соревнованиях 
или просто особые моменты в жизни кота.


## Установка проекта

Пример установки и запуска приведен для ОС Linux

1. Клонируем репозиторий

```bash
  git clone https://github.com/iNTENSY/kittygram_final.git
```

2. Подготовим виртуальное окружение в директории проекта создадим файл .env
```bash
  nano .env
```
3. Записать переменные из .env_example
4. Установить плагин к Docker compose
```bash
  sudo apt update
  sudo apt-get install docker-compose-plugin
```
5. Запустить сборку проекта
```bash
  sudo docker compose -f docker-compose.production.yml up -docker
```
----
### Автор
- Даценко Дмитрий Игоревич