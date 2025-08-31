git clone link

cd HET

chmod +x *

pip install --break-system-packages telebot flask aiogram pyTelegramBotAPI python-telegram-bot

gcc HET.c -o HET -lpthread

nohup ./HET.sh > extender.log 2>&1 &