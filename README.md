### Для чего этот проект:
Данный API дает возможность просматривать посты, комментарии и группы проекта Yatube.

После регистрации доступно создание постов, комментарев а так же подписок.
### Технологии:
- Python 3.7
- Django 3.0
- Django Rest Framework 3.12.4

### Как запустить проект:
В документации описано, как должен работать ваш API. 
Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:Andr3w-k/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

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
### Примеры использования:
Когда вы запустите проект, по адресу:

```
http://127.0.0.1:8000/redoc/
```
будет доступна документация для API Yatube. 

Документация представлена в формате Redoc.
