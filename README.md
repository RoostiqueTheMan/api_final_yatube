### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/api_final_yatube.git

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
py -m venv env
```

```
source vens/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
py -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
py manage.py migrate
```

Запустить проект:

```
py manage.py runserver
```