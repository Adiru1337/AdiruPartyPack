1. Подготовка окружения
Открой Termux и обнови пакеты:

pkg update && pkg upgrade -y

pkg install python git -y

pkg install rust -y

2. Создание и активация виртуального окружения (рекомендуется)
   
python -m venv venv

source venv/bin/activate

3. Установка зависимостей
Установка aiogram и aiohttp с обходом ошибок сборки:

AIOHTTP_NO_EXTENSIONS=1 pip install aiohttp

Далее устанавливаем aiogram:

pip install aiogram=2.25.2

Установка остальных зависимостей из requirements.txt

pip install -r requirements.txt

4. Запуск
   
cd AdiruPartyPack

python app.py

Как обновить AdiruPartyPack:

rm -rf AdiruPartyPack

git clone https://github.com/Adiru1337/AdiruPartyPack.git

AdiruPartyPack V2.0

Обновления вряд-ли будут, геморойный проект заебало

