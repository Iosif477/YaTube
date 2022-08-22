# Yatube

### Технологии:
- Python 3.7
- Django 2.2

## Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/pozdnysheva/YaTube.git
```

```
cd yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

### Автор
- [Позднышева Наталья](https://github.com/pozdnysheva "Github page")
