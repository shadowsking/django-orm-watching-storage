# Пульт охраны банка


### Как установить
Версия python >= 3.5.0

1) Клонирование проекта
```bash
git clone https://github.com/shadowsking/django-orm-watching-storage.git
cd django-orm-watching-storage
```

2) Создание виртуального окружения
```bash
python -m venv venv
source venv/scripts/activate
```

3) Установка зависимостей
```bash
pip install -r requirements.txt
```

Скопировать '.env.example' в новый '.env' и заполнить переменные:
- DB_HOST
- DB_NAME
- DB_USER
- DB_PASSWORD
- SECRET_KEY
