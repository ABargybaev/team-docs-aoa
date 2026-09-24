## Наш DevOps проект

## Описание проекта
Проект по настройке командной документации и отработке навыков работы с Git и GitHub.

## Команда
Баргыбаев Азамат - тимлид
Токтобекова Аяна — CI/CD / QA Engineer
Султанова Оминахан - DevOps/Infrastructure Engineer

## Стек технологий
- Docker
- Nginx
- Kubernetes
- Terraform
- Linux (Ubuntu)
- Git GitHub

## Инструкции по запуску
1. Скопировать репозиторий: `git clone https://github.com/ABargybaev/team-docs-aoa.git`
2. Перейти в папку проекта: `cd team-docs-aoa`
3. Собрать Docker-образ: `docker build -t my-app .`
4. Запустить контейнер: `docker run -d -p 8080:80 my-app`
5. Проверить работоспособность приложения: `curl http://localhost:8080`
6. Посмотреть логи контейнера: `docker logs my-app`
