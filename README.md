Материалы касающиеся создания собственного фреймворка web-представления

Install:
Запускать будем скрипт в модуле fwsgi.py.
Для начала запускать будем через Uwsgi. Но эту библиотеку сперва нужно установить. А это танцы с бубном. Будут нужны некоторые доп. библиотеки.
sudo add-apt-repository universe
sudo apt update
sudo apt install python-pip
Теперь:
pip install uwsgi
