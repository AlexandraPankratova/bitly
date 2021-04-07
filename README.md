# Работа с Bitly

Программа создана для перевода длинных ссылок в битлинки или для подсчета количества кликов по битлинку.

## Перед началов работы
1. Необходимо получить `GENERIC ACCESS TOKEN`. Для этого:

    1.1. Зарегистрируйтесь на сайте [Bitly](https://bit.ly).

    1.2. Затем получите свой уникальный `GENERIC ACCESS TOKEN`, 
    зайдя в раздел `PROFILE SETTINGS`, 
    далее в раздел `GENERIC ACCESS TOKEN`.

2. Необходимо передать токен в main.py. Для этого:

    2.1. В каталоге проекта создайте пустой файл .env.

    2.2 В файл .env запишите `GENERIC ACCESS TOKEN` в следующем формате:

    ```
    BITLY_TOKEN=Bearer Ваш_GENERIC_ACCESS_TOKEN
    ```
3. Необходимо загрузить в виртуальное окружение библиотеки из файла requirements.txt. 
Для этого уже активировав виртуальное окружение, выполните следующую команду:

    ```bash
    pip install -r requirements.txt
    ```
## Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).
