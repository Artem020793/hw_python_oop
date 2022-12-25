# Модуль фитнес-трекера
### Запуск проекта в dev-режиме
1. Клонировать репозиторий:
2. Перейти в папку с проектом:
3. Установить виртуальное окружение для проекта:
```
python -m venv venv
``` 
4. Активировать виртуальное окружение для проекта:
```
# для OS Lunix и MacOS
source venv/bin/activate

# для OS Windows
source venv/Scripts/activate
```
5. Установить зависимости:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
6. Выполнить миграции на уровне проекта:
```
cd yatube
python3 manage.py makemigrations
python3 manage.py migrate
```
7. Запустить проект локально:
```
python3 manage.py runserver

# адрес запущенного проекта
http://127.0.0.1:8000
```
8. Зарегистирировать суперпользователя Django:
```
python3 manage.py createsuperuser

# адрес панели администратора
http://127.0.0.1:8000/admin
```
### Автор проекта
Артем Римша
