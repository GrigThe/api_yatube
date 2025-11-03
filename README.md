## Как запустить проект:
### Клонировать репозиторий и перейти в него в командной строке:

git clone https://github.com/GrigThe/api_yatube
cd api_yatube
### Создание и активация venv:

python3 -m venv env
source venv/bin/activate
python3 -m pip install --upgrade pip
### Установить зависимостей:

pip install -r requirements.txt
### Выполнить миграции:

python3 manage.py migrate
### Запустить проект:

python3 manage.py runserver

