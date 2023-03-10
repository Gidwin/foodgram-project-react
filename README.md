# praktikum_new_diplom
## Описание проекта

Foodgram это ресурс для публикации рецептов.
Пользователи могут создавать свои рецепты, читать рецепты других пользователей, подписываться на интересных авторов, добавлять лучшие рецепты в избранное, а также создавать список покупок и загружать его в pdf формате

## Установка проекта локально

* Склонировать репозиторий на локальную машину:
```bash
git clone https://github.com/skarabey147/foodgram-project-react.git
cd foodgram-project-react
```

* Cоздать и активировать виртуальное окружение:

```bash
python -m venv venv
```

```bash
source venv/bin/activate
```

* Перейти в директирию и установить зависимости из файла requirements.txt:

```bash
cd backend/
pip install -r requirements.txt
```

* Выполните миграции:

```bash
python manage.py migrate
```

* Запустите сервер:
```bash
python manage.py runserver
```

ip -- http://158.160.24.80/
админка лог admin@admin.com - пас admin
