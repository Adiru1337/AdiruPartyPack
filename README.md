Установи git, если ещё не установлен:
pkg update && pkg upgrade
pkg install git

Склонируй репозиторий:
git clone https://github.com/Adiru1337/AdiruPartyPack.git

Перейди в папку с проектом:
cd AdiruPartyPack

Установи Python (если ещё не установлен) и виртуальное окружение
pkg install python
python3 -m venv venv
source venv/bin/activate

В папке проекта, если есть файл requirements.txt, то:
pip install --upgrade pip
pip install -r requirements.txt

Если файла нет, можно установить вручную нужные пакеты, например:
pip install aiogram fastapi uvicorn

Если это Telegram бот на aiogram, запускай так:
python AdiruPartyPack.py
