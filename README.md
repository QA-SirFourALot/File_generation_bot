<h2>Телеграм бот, помогающий тестировщику сгенерировать файл</h2>

> **Статус проекта:**
>
> Не поддерживается (временно не активен) 

## Цели и Задачи
* Бот принимает на входе тип и размер файла, а на выходе отдаёт сам файл.
* Это может пригодиться, когда на сайте есть ограничение на размер загрузки фото и нужно проверить граничные значения.

## 🖼 Скриншоты

Стартовое меню:

![image](https://raw.githubusercontent.com/QA-SirFourALot/File_generation_bot/main/Start_menu.png)

После выбора файла:

![image](https://raw.githubusercontent.com/QA-SirFourALot/File_generation_bot/main/e2e.png)

## 💻 Технологии

* Python
* Библиотека `telebot`

## ⏬ Установка на локальном компьютере

1. Скачать проект

2. Создать бота и через [@BotFather](https://t.me/BotFather) и вставить в проекте свой токен от бота

3. Создаём виртуальное окружение внутри папки проекта.
Команды для Windows:

Если вы указали путь до python.exe

``` markdown
PS> python -m venv venv
```
Если вы не указывали путь до python.exe

``` markdown
PS> C:\Users\Name\AppData\Local\Programs\Python\Python310\python -m venv venv
```
Теперь, когда вы создали виртуальное окружение, необходимо запустить скрипт активации

``` markdown
PS> venv\Scripts\activate
(venv) PS>
```
4. Устанавливаем библиотеки

``` markdown
(venv) PS> python -m pip install pyTelegramBotAPI
```

5. Запускаем
``` markdown
python main.py
```

## Автор

Клим Истомин ([@SirFouralot](https://t.me/SirFouralot))
