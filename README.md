### Как запустить проект

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Heim-Sendir/api_final_yatube.git
```

```
cd api_final_yatube
```

Создать и активировать виртуальное окружение:

```
py -m venv venv
```

* Если у вас Linux/macOS
    ```
    source venv/bin/activate
    ```

* Если у вас windows
    ```
    source venv/Scripts/activate
    ```

```
py -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить тесты:
```
pytest
```

Запустить проект:

```
python3 manage.py runserver
```

Для просмотра документации запустите проект и перейдите по адресу:
```
127.0.0.1:8000/redoc
```