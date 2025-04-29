### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone 
```

```
cd what_to_watch
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```
или для пользователей Windows

```
source env/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Запустить проект:

```
flask run
```

└── what_to_watch
    ├── instance
    │   └── db.sqlite3    <-- Файл базы данных
    ├── migrations
    │   ├── versions
    │   ├── alembic.ini
    │   ├── env.py
    │   ├── README
    │   └── script.py.mako
    ├── opinions_app
    |   ├── static     <-- Директория со статикой
    |   ├── templates     <-- Директория с шаблонами
    |   ├── __init__.py
    |   ├── cli_commands.py     <-- Новый файл с функциями пользовательских команд
    |   ├── error_handlers.py     <-- Новый файл с обработчиками ошибок
    |   ├── forms.py     <-- Новый файл с формами
    |   ├── models.py     <-- Новый файл с моделями
    |   └── views.py     <-- Новый файл с view-функциями
    ├──venv
    ├──.env
    ├──.gitignore
    ├── opinions_app.py
    ├── opinions.csv
    ├── README.md
    ├── requirements.txt
    └── settings.py    <-- Новый файл с настройками приложения 