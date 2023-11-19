# Приложение (API) для учёта трат пользователя

## Документация
Описание и схема БД находятся в "docs"

## Старт проекта

Создать ".env" файл с ".env.example" ключами из директории "config" и заполнитиь их необходимыми значениями.

Установить зависимости:
'poetry install'

Активировать виртуальное окружение:
'poetry shell'

Применить миграции:
'poetry run python manage.py migrate'

Создать суперпользователя для доступа к панели администратора:
'poetry run python manage.py createsuperuser'

Запуск приложения:
'poetry run python manage.py runserver'

## Запуск тестов
'poetry run pytest'

## Панель администратора
'http://localhost:8000/admin/'