# AdiruPartyPack V2.0

![AdiruPartyPack](https://raw.githubusercontent.com/Adiru1337/AdiruPartyDraw/refs/heads/main/partypack.png)

---

## Подготовка окружения

1. Открой Termux и обнови пакеты:


1. Подготовка окружения
Открой Termux и обнови пакеты:
```bash
pkg update && pkg upgrade -y

pkg install python git -y

pkg install rust -y
```
2. Создание и активация виртуального окружения (рекомендуется)
```bash
python -m venv venv

source venv/bin/activate
```
3. Установка зависимостей
Установка aiogram и aiohttp с обходом ошибок сборки:
```bash
AIOHTTP_NO_EXTENSIONS=1 pip install aiohttp
```
Далее устанавливаем aiogram:
```bash
pip install aiogram=2.25.2
```
Установка остальных зависимостей из requirements.txt
```bash
pip install -r requirements.txt
```
4. Запуск
```bash
cd AdiruPartyPack

python app.py
```
Как обновить AdiruPartyPack:
```bash
rm -rf AdiruPartyPack

git clone https://github.com/Adiru1337/AdiruPartyPack.git
```
# AdiruPartyPack V2.0

Обновления вряд-ли будут, геморойный проект заебало


------------------------------------------------------------


