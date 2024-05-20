
# Простое веб-приложение на Flask

Это проект простого веб-приложения, написанного фреймворке Flask языка Python.

## Установка

1. Установите Python, если он не установлен. Его можно скачать с [официального сайта](https://www.python.org/downloads/).

2. Клонируйте репозиторий на локальную машину:
```
git clone https://github.com/DroidVedroid/TiSKPO_webapp_project
```

3. Перейдите в каталог с проектом:
```
cd TiSKPO_webapp_project
```

4. Установите виртуальное окружение
```
python -m venv venv
```
5. Активируйте виртуальное окружение
	Windows: `venv\Scripts\activate`
	Unix: `source venv/bin/activate`

5. Установите зависимости:
```
pip install -r requirements.txt
```

## Запуск

1. Запустите приложение:
```
python app.py
```

2. Откройте браузер и перейдите по адресу `http://localhost:5000` для просмотра приложения.
3. Для остановки веб-сервера используйте CTRL+C в комндной строке.

## Структура проекта

- **templates/**: каталог, содержащий HTML-шаблоны;
- **static/**: каталог, содержащий статические файлы, такие как CSS, JavaScript и изображения;
- **app.py**: основной файл приложения, содержащий код Flask;
- **database.py**: файл, содержащий настройки базы данных и создания экземпляра SQLAlchemy;
- **models.py**: файл с определением структуры базы данных;
- **app.db**: SQLite база данных проекта;
- **requirements.txt**: файл, содержащий список зависимостей Python.




