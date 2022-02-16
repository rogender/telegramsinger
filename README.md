# telegramsinger
Небольшой проект, который поет песню, но от вашего аккаунта в телеграмме

![Работа бота](https://github.com/rogender/telegramsinger/blob/main/screenshots/telegram_song.jpg) 

## Установка и использование
Необходимо скачать [Termux](https://play.google.com/store/apps/details?id=com.termux) для Андроид(Если кратко, то это эмулятор терминала из Linux)

Дальше нужно ввести последовательно следующие команды:
- apt-get update
- apt-get install git python -y
- pip install pyrogram
- git clone https://github.com/rogender/telegramsinger.git
- cd telegramsinger
- python index.py

Скорее всего, у вас попросят номер телефона и код, который придет вам в Telegram
![Выбор аккаунта и его подтверждение](https://github.com/rogender/telegramsinger/blob/main/screenshots/termux_commands.jpg) 

Чтобы от вашего лица начались писать сообщения, напишите в любом чате "Хочешь песню?" (без кавычек)

## Изменение текста песни
Если вам нужно изменить песню, то пишем последовательно следующие команды:
- pkg install micro
- cd telegramsinger
- micro song

Изменяете текст, дальше нажимаете ctrl+s и ctrl+q

