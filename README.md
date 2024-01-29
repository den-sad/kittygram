# Проект преназначен для отработки практических навыков работы с API

Реализованы методы GET и POST

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:den-sad/kittygram.git
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
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
### URL адрес API http://127.0.0.1:8000/cats/

### пример POST запроса для добавления данных о питомце

```
    {
        "name": "browny",
        "color": "brown",
        "birth_year": 2011
    }
```
