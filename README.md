### Описание: 
API для социальной сети Yatube. Реализована возможность просмотра и добавления постов,
оставление комментариев, подписка на авторов.

### Технологии:

Python 3.9,

Django 2.2.16,

DjangoORM,

Django REST Framework,

Djoser,

SQLite

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/anton-sivko/api_final_yatube
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
Windows: python3 -m venv venv
Ubuntu:  python39 -m venv venv
```

```
Windows: source venv/scripts/activate
Ubuntu:  source venv/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
### Документация:

После запуска проекта документация доступна по адресу http://127.0.0.1:8000/redoc.
