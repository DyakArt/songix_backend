# Songix Backend

Это серверная часть веб-приложения **Songix**, созданная с использованием Django REST API для управления регистрацией и авторизацией пользователей. В проекте используется база данных PostgreSQL.

## Содержание
- [Обзор проекта](#обзор-проекта)
- [Установка](#установка)
- [Использование](#использование)

## Обзор проекта
Проект **Songix** — это платформа для взаимодействия с музыкальными коллекциями, поддерживающая функции регистрации и авторизации с помощью REST API.

## Установка
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/DyakArt/songix_backend.git
   ```
2. Перейдите в директорию проекта:
   ```bash
   cd songix_backend
   ```
3. Создайте и активируйте виртуальное окружение:
   ```bash
   python -m venv venv
   source venv/bin/activate   # для Windows: venv\Scripts\activate
   ```
4. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```
5. Выполните миграции базы данных:
   ```bash
   python manage.py migrate
   ```
6. Запустите сервер разработки:
   ```bash
   python manage.py runserver
   ```

## Использование
После запуска сервера разработки, отправляйте запросы по адресу `http://127.0.0.1:8000/`, чтобы получить доступ к приложению.

[Songix Frontend](https://github.com/vladkrakhmalev/Songix)