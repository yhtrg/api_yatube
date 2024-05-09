# API Yatube
### Описание
API_Yatube - это REST API для cоциальной сети блогеров Yatube.
- Аутентификация по JWT-токену
- Работает со всеми модулями Yatube: постами, комментариями, группами, подписчиками
- Поддерживает методы GET, POST, PUT, PATCH, DELETE
### Технологии
- Python 3.9
- Django
- DjangoRestFramework
- DjangoRestFramework-SimpleJWT 
- Djoser
- PyJWT
### Запуск проекта в dev-режиме
- Выполните команды:
```
git clone ...
cd api_yatube
```
- Установите и активируйте виртуальное окружение
```
python -m venv venv
source venv/Scripts/activate
```
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
```
- Выполните миграции:
```
python3 manage.py migrate
```
- Запустите проект:
```
python3 manage.py runserver
```
### Создание описания
```
Описание проекта было создано при помощи сайта readme.so/editor
```
### Автор
Артём Карташян
#### (https://github.com/yhtrg)
