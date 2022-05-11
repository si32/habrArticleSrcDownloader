Скрипт python3 для скачивания исходников статей с [habr](https://habr.com/)  
Тестировал на **python 3.6.9**, под **Linux Mint 19.3**.


### Как использовать:

```bash
apt-get install python3-lxml
pip3 install -r requirements.txt
./src/main.py "user_name"
```

Например:

```bash
./src/main.py jessy_james
```

Взять имя пользователя можно из ссылки профиля

<img src="https://habrastorage.org/webt/4e/ur/ml/4eurmlni9b4f15fuqpuz4wrolmq.png" />


Если все было сделано успешно, то Вы увидите примерно следующее:
```bash
./src/main.py jessy_james
[info]: Скачивается: C/C++ из Python (ctypes) на Android
[info]: Директория: 16 C C++ из Python (ctypes) на Android создана
[info]: Директория: picture создана
[info]: Статья: C C++ из Python (ctypes) на Android сохранена
[info]: Скачивается: Своя docking station для ноутбука
[info]: Директория: 15 Своя docking station для ноутбука создана
[info]: Директория: picture создана
[info]: Статья: Своя docking station для ноутбука сохранена
[info]: Скачивается: Tango Controls hdbpp-docker
[info]: Директория: 14 Tango Controls hdbpp-docker создана
[info]: Директория: picture создана

...

[info]: Скачивается: Игрушка ГАЗ-66 на пульте управления. Часть 2
[info]: Директория: 2 Игрушка ГАЗ-66 на пульте управления. Часть 2 создана
[info]: Директория: picture создана
[info]: Статья: Игрушка ГАЗ-66 на пульте управления. Часть 2 сохранена
[info]: Скачивается: Игрушка ГАЗ-66 на пульте управления. Часть 1
[info]: Директория: 1 Игрушка ГАЗ-66 на пульте управления. Часть 1 создана
[info]: Директория: picture создана
[info]: Статья: Игрушка ГАЗ-66 на пульте управления. Часть 1 сохранена

```
