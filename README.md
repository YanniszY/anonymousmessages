# Anonymous Telegram Bot

Этот проект представляет собой Telegram-бота, который генерирует уникальную ссылку для каждого пользователя. Люди могут делиться этими ссылками, чтобы получать анонимные сообщения от других.

## Описание

**Anonymous Telegram Bot** позволяет пользователям получить уникальную ссылку, которую можно разместить в соцсетях, форумах или отправить напрямую другим людям. Любой, у кого есть эта ссылка, может отправить анонимное сообщение, которое будет доставлено в Telegram владельцу ссылки.

![logo](img/logo.png)

### Основные возможности

- Генерация уникальной ссылки для каждого пользователя.
- Отправка анонимных сообщений через эту ссылку.
- Поддержка безопасности и приватности: отправители остаются анонимными.
- Легкая интеграция и использование через Telegram.

## Установка и настройка

### Требования

- Python 3.12+
- Telegram Bot API токен

### Установка

1. Клонируйте репозиторий: https://github.com/YanniszY/anonymousTGmessages.git

    ```bash
    git clone 
    cd anonymousTGmessages
    ```

2. Установите зависимости:

    ```bash
    pip install -r requirements.txt
    ```

3. Создайте файл `.env` и добавьте туда ваш Telegram Bot API токен:

    ```env
    BOT_TOKEN="ваш_токен_бота"
    ```

4. Запустите бота:

    ```bash
    python bot.py
    ```

5. Запустите серврер Redis:
   ```bash
   redis-server
   ```

## Использование

1. Запустите бота в Telegram.
2. Введите команду `/start`, чтобы получить вашу уникальную ссылку.
3. Поделитесь этой ссылкой где угодно.
4. Получайте анонимные сообщения прямо в Telegram!

## Вклад в проект

Если вы хотите внести свой вклад в развитие проекта:

1. Сделайте форк репозитория.
2. Создайте новую ветку (`git checkout -b feature/YourFeature`).
3. Внесите изменения и сделайте коммит (`git commit -m 'Добавлено что-то новое'`).
4. Запушьте ветку (`git push origin feature/YourFeature`).
5. Создайте Pull Request.
