### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/scanlin-prog/kittygram-api
```

```
cd kittygram-backend
```

Cоздать и активировать виртуальное окружение:

* Если у вас Linux/macOS


    ```
    Использовать python3
    ```

* Если у вас windows

    ```
    Использовать python
    ```

```
py -3.9 -m venv env
source env/bin/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

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
