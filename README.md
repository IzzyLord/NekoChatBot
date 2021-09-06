# NekoChatBot
Just another Telegram AI chat bot written in Python using Pyrogram.

A public running instance can be found on telegram as [@Neko_Chat_Bot](https://t.me/Neko_Chat_Bot).

## Requirements

- Python 3.7 or higher.
- A [bot token](//t.me/botfather).


## Installation

```sh
$ git clone https://github.com/IzzyLord/NekoChatBot
$ cd NekoChatBot
$ pip3 install -U -r requirements.txt
$ cp sample_config.py config.py
```
Edit `config.py` with your own values.
```sh
$ python3 Neko.py
```


## Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/IzzyLord/NekoChatBot/tree/master)


## Docker

Follow Installation Guide.
```sh
$ sudo docker build -t Neko .
$ sudo docker run Neko
```
