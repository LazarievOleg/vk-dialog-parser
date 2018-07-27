Код написан на Python 3+. 
Соответственно нужно его установить:
https://www.python.org/ftp/python/3.7.0/python-3.7.0.exe

При установке выбрать Custom installation, 
Optional Features: поставить галочку install PIP
Advanced Opt.: оставить как есть

Скачиваем сам парсер:
https://github.com/Fl0ydR0se/vk-dialog-parser/archive/master.zip
затем разархивируем его в удобное место.

Далее запускаем командную строку из папки с парсером.

Установим нужные библиотеки, в командной строке пишем и нажимаем enter:
pip install aiohttp
потом
pip install vk_api

Далее запускаем сам парсер (пишем или копируем в консоль и нажимаем энтер):

python vk.py --id <friend|chat>

friend vk id (example: get friend id 1234567890 from url https://vk.com/im?sel=1234567890);
chat vk id (example: get chat id c123 from url https://vk.com/im?sel=c123).

Далее вводим логин и пароль от своей страницы ВК. 
Получаем тонну фоток.
