<div align="center">

# [![beast](https://user-images.githubusercontent.com/80776324/230666266-f4516de9-cbc8-4d11-ad39-a7f6d1bfa00a.png)](https://t.me/beast_bomberr_bot)

# Beast Bomber 💣
  
​​​​​​</br> [![docker_hub](https://badgen.net/badge/docker/docker/white?icon=docker&label)](https://hub.docker.com/r/un1cum/beast_bomber) [![Button](https://badgen.net/badge/un1cum/un1cum/white?icon=github&label)](https://github.com/un1cum) [![Button](https://badgen.net/badge/fork/fork/white?icon=github&label)](https://github.com/un1cum/Beast_Bomber/fork)
​​​​​​</br> [![Button](https://badgen.net/badge/patreon/patreon/white?icon=patreon&label)](https://www.patreon.com/un1cum) [![Button](https://badgen.net/badge/replit/replit/white?icon=bitcoin-lightning&label)](https://replit.com/@un1cum/Beast-Bomber) [![Button](https://badgen.net/badge/discord/discord/white?icon=discord&label)](https://discord.gg/qkK4NG4ARU)

</div>

# 📌 Menu / Меню

📌 [<kbd>EN</kbd>](#-en)
- [<kbd>Installation</kbd>](#-installation)
- [<kbd>SMS attack</kbd>](#-sms-attack)
- [<kbd>Discord attack</kbd>](#-discord-attack)
- [<kbd>DDoS attack</kbd>](#-ddos-attack)
- [<kbd>Email attack</kbd>](#-email-attack)
- [<kbd>Telegram attack</kbd>](#-telegram-attack)
- [<kbd>Problems and their solutions</kbd>](#-problems-and-their-solutions)
- [<kbd>Contributors</kbd>](#-contributors)
- [<kbd>Donate for coffee</kbd>](#-donate-for-coffee)

📌 [<kbd>RU</kbd>](#-ru)
- [<kbd>Установка</kbd>](#-установка)
- [<kbd>СМС атака</kbd>](#-sms-атака)
- [<kbd>Discord атака</kbd>](#-discord-атака)
- [<kbd>DDoS атака</kbd>](#-ddos-атака)
- [<kbd>Email атака</kbd>](#-email-атака)
- [<kbd>Telegram attack</kbd>](#-telegram-атака)
- [<kbd>Проблемы и их решения</kbd>](#-проблемы-и-их-решения)
- [<kbd>Вклады в проект</kbd>](#-вклады-в-проект)
- [<kbd>Автору на кофе</kbd>](#-автору-на-кофе)

# 📌 EN

📌 **Beast Bomber in Telegram: https://t.me/beast_bomberr_bot**

📌 **Beast Bomber in replit: https://replit.com/@un1cum/Beast-Bomber**

📌 **Discord server: https://discord.gg/beast-bomber-team | https://discord.gg/qkK4NG4ARU**

![screenshot](https://user-images.githubusercontent.com/80776324/214398611-d862b400-9ebb-4c51-ac7f-80643849301a.png)

`Possibilities`
* SMS attack
* Email attack
* Discord attack
* Telegram attack
* DDoS attack
* Multilanguage

# 📌 Installation

📌 [<kbd>Methods</kbd>](#-methods)
- [<kbd>Docker</kbd>](#-docker)
- [<kbd>Manual</kbd>](#-manual)

## 📌 Docker

<div align="center">

![docker](https://user-images.githubusercontent.com/80776324/230794354-00b25763-fec2-4278-841a-1c624863ab60.png)

​​​​​​</br>[![docker_hub](https://badgen.net/badge/docker/docker/white?icon=docker&label)](https://hub.docker.com/r/un1cum/beast_bomber)

</div>

`Image url: https://hub.docker.com/r/un1cum/beast_bomber`

`If you don't have docker, you can install it using these instructions: https://docs.docker.com`

- You need to enter the following command to download the image:

```
docker pull un1cum/beast_bomber
```

- To start the bomber, enter this command:

```
docker run -it un1cum/beast_bomber
```

**Done!**

## 📌 Manual

![tutorial](https://user-images.githubusercontent.com/80776324/230665884-f52bb3d8-b20d-4275-9afc-0f5068eeaf82.gif)

`To run the beast bomber you need to download Python: https://www.python.org`

```
git clone https://github.com/un1cum/Beast_Bomber
```

`P.S`
- If you don't have git, you need to install it: https://git-scm.com/downloads
- If you install Beast Bomber manually, without git, be sure to delete the .gitkeep file in the input\telegram_accounts folder

`First setup`

- To get started, you need to install the necessary Python libraries. Go to the Beast_Bomber folder and enter this command in cmd or terminal:  

```
pip install -r requirements.txt
```

- For a DDoS attack to work correctly, you need to enter **proxies** into the input\proxies.txt file or automatically parse them using the built-in function
- For the Telegram attack to work, you need to put the Telegram accounts in **tdata** format (each account in a separate folder) in the input\telegram_accounts folder
- To make email spam work, you need to put email accounts in the format **email:password** in the input\email_accounts.txt file
- For discord spam to work, you must place **tokens** from discord accounts in the file input\discord_accounts.txt

`Launch`

```
python beast.py
```

**Done!**

# 📌 SMS attack

There are many spam services at your disposal! Beast Bomber supports **Russian and Kazakh** phone numbers.

# 📌 Discord attack

To start a Discord attack, you need to specify the **target ID**, it can be found in the url of the discord dialog in your browser.


![discord](https://user-images.githubusercontent.com/80776324/230663913-d68dbf58-0738-4501-9539-17daf0d36753.png)

# 📌 DDoS attack

**Test results from https://dstat.cc**

![screenshot](https://user-images.githubusercontent.com/80776324/214398918-81d488c7-e23a-4dc3-864b-3b82b1c55571.png)

| Threads | Attack time |
|---------|-------------|
|   40    | 60 seconds  |

# 📌 Email attack

Beast Bomber supports the following email services (from which spam will be sent): **mail.ru, yahoo, rambler.**

# 📌 Telegram attack

The attack occurs as follows:


Beast Bomber logs into the accounts that you put in your input\telegram_accounts folder and sends the message you write from them.


You can buy tdata telegram accounts here: [click](https://darkstore.biz/?search_triggered=true&category_id=43&group_id=&sort=-purchase_counter&feature=) **(not advertising)**

# 📌 Problems and their solutions

``If you see something like this:``

![screenshot](https://i.ibb.co/XWNtL0S/Screenshot-1.png "no module named") 

This means that you don't have the library that is specified in the error, in this case: "_ctypes". You need to enter in the terminal or cmd:

* pip install <the name of the required library> 

``Example:``

```
pip install _ctypes
```

``If you install Beast Bomber on the termux:``

You may have a problem installing the **opentele** library, to fix it enter the following command: 

```
pkg install pyqt5 python-pyqtwebengine
```

then reinstall the **opentele** library.

# 📌 Contributors

| Sr.No. | Name | Date of contribution |
|--------|------|----------------------|
|1|[PalkerCode](https://github.com/PalkerCode)|Apr 10, 2022|
|2|[hiikion](https://github.com/hiikion)|Jul 4, 2022|
|3|[NameNami](https://github.com/NameNami)|Jul 27, 2022|
|4|[xpghard](https://github.com/xpghard)|March 30, 2023|

**Thank you all for your contributions to the project ❤️**

# 📌 Donate for coffee

`Patreon`
* **URL: https://www.patreon.com/un1cum**

`Boosty`
* **URL: https://boosty.to/un1cum**

`Crypto wallets`


* ![BNB](https://user-images.githubusercontent.com/80776324/230691108-ecd10132-af58-4064-8c44-ad10f6f55dd1.png) **BNB: 0x96a0B6E4274771D5f3F8e59564b58C35D74D8Cc1**


* ![BTC](https://user-images.githubusercontent.com/80776324/230691099-1422c66c-099e-49f2-adee-b48fa9533c0c.png) **BTC: bc1qxfvstf99kyuc5x5uugxtsh3m6w3a73ruzfav7e**


* ![ETH](https://user-images.githubusercontent.com/80776324/230691090-32c937b9-61bc-4eeb-b058-c46c8fc250ac.png) **ETH: 0x96a0B6E4274771D5f3F8e59564b58C35D74D8Cc1**


* ![LTC](https://user-images.githubusercontent.com/80776324/230691072-c3bc7a2b-7e4e-4a4b-ab56-e82ee5ffb717.png) **LTC: ltc1qudx4ge8zvncqpdtl5mshfqjxzyvg43f27ysqjt**


* ![USDT](https://user-images.githubusercontent.com/80776324/230691044-44802059-c433-4de5-a221-0f69c0b7c660.png) **USDT (TRC-20): TKVs4Bt63mVGSYth7HSvNQBk8Xp1UKMH9Y**


# 📌 RU

📌 **Beast Bomber в Telegram: https://t.me/beast_bomberr_bot**

📌 **Beast Bomber на replit: https://replit.com/@un1cum/Beast-Bomber**

📌 **Discord сервер: https://discord.gg/beast-bomber-team | https://discord.gg/qkK4NG4ARU**

![screenshot](https://user-images.githubusercontent.com/80776324/214398819-4cf892ba-aa55-456f-86ed-584dde45ab20.png)

`Возможности`
* SMS атака
* Email атака
* Discord атака
* Telegram атака
* DDoS атака
* Мультиязычность

# 📌 Установка

📌 [<kbd>Методы</kbd>](#-methods)
- [<kbd>Докер</kbd>](#-докер)
- [<kbd>Вручную</kbd>](#-вручную)

## 📌 Докер

<div align="center">

![docker](https://user-images.githubusercontent.com/80776324/230794354-00b25763-fec2-4278-841a-1c624863ab60.png)

​​​​​​</br>[![docker_hub](https://badgen.net/badge/docker/docker/white?icon=docker&label)](https://hub.docker.com/r/un1cum/beast_bomber)

</div>

`Ссылка на образ: https://hub.docker.com/r/un1cum/beast_bomber`

`Если у вас нету docker, вы можете установить его, следуя официальным инструкциям: https://docs.docker.com`

- Чтобы загрузить образ, введите следующую команду:

```
docker pull un1cum/beast_bomber
```

- Чтобы запустить бомбер, введите это:

```
docker run -it un1cum/beast_bomber
```

**Готово!**

## 📌 Вручную

![tutorial](https://user-images.githubusercontent.com/80776324/230665884-f52bb3d8-b20d-4275-9afc-0f5068eeaf82.gif)

`Для работы beast bomber вам нужно установить Python: https://www.python.org`

```
git clone https://github.com/un1cum/Beast_Bomber
```

`P.S`
- Если у вас нет git, вам нужно установить его: https://git-scm.com/downloads
- Если будете устанавливать Beast Bomber вручную, без git, то обязательно удаляйте файл .gitkeep в папке input\telegram_accounts

`Первая установка`
- Чтобы начать работу, вам нужно установить необходимые библиотеки Python. Зайдите в папку Beast_Bomber и введите в cmd или terminal эту команду: 
```
pip install -r requirements.txt
```
- Для корректной работы DDoS атаки необходимо поместить прокси в файл input\proxies.txt или автоматически спарсить их с помощью встроенной функции
- Чтобы атака Telegram работала, необходимо поместить аккаунты Telegram в формате **tdata** (каждый аккаунт в отдельной папке) в папку input\telegram_accounts
- Чтобы спам по электронной почте работал, вам нужно поместить учетные записи электронной почты в формате **email:пароль** в файл input\email_accounts.txt
- Для того, чтобы работал спам в Discord, вы должны поместить **токены** от аккаунтов Discord в файл input\discord_accounts.txt

``Запуск``
```
python beast.py
```

**Готово!**

# 📌 SMS атака

В вашем распоряжении множество спам сервисов! Beast Bomber поддерживает **русские и казахские** номера телефонов.

# 📌 Discord атака

Чтобы начать атаку Discord, вам нужно указать **ID цели**, его можно найти в url диалога discord в вашем браузере.


![discord](https://user-images.githubusercontent.com/80776324/230664016-2cb6d111-15fb-422e-ae3d-d38ead9bcbb2.png)

# 📌 DDoS атака

**Результаты теста с https://dstat.cc**

![screenshot](https://user-images.githubusercontent.com/80776324/214398918-81d488c7-e23a-4dc3-864b-3b82b1c55571.png)

| Потоки  | Время атаки |
|---------|-------------|
|   40    |  60 секунд  |

# 📌 Email атака

Beast Bomber поддерживает следующие почтовые сервисы (с которых будет рассылаться спам): **mail.ru, yahoo, rambler.**.

# 📌 Telegram атака

Атака происходит следующим образом:


Beast Bomber входит в аккаунты, которые вы поместили в папку input\telegram_accounts и отправляет от них сообщение, которое вы указали.


Купить telegram аккаунты в формате tdata можно тут: [тык](https://darkstore.biz/?search_triggered=true&category_id=43&group_id=&sort=-purchase_counter&feature=) **(не реклама)**

# 📌 Проблемы и их решения

``Если у вас похожая ошибка:``

![screenshot](https://i.ibb.co/XWNtL0S/Screenshot-1.png "no module named") 

Это означает, что у вас отсутствует нужная библиотека pip, в этом случае: "_ctypes". Откройте терминал, cmd или что там у вас и пишите:

* pip install <имя отсутствующей библиотеки>

``Пример:``

```
pip install _ctypes
```

``Если вы устанавливаете Beast Bomber на termux:``

У вас может возникнуть пробоема с установкой библиотеки **opentele**, чтобы исправить её, введите следующую команду: 

```
pkg install pyqt5 python-pyqtwebengine
```

затем повторите установку **opentele**.

# 📌 Вклады в проект

| Строка | Имя | Дата вклада |
|--------|------|----------------------|
|1|[PalkerCode](https://github.com/PalkerCode)|Апрель 10, 2022|
|2|[hiikion](https://github.com/hiikion)|Июль 4, 2022|
|3|[NameNami](https://github.com/NameNami)|Июль 27, 2022|
|4|[xpghard](https://github.com/xpghard)|Март 30, 2023|

**Спасибо всем за ваши вклады в проект ❤️**

# 📌 Автору на кофе

`Patreon`
* **Ссылка: https://www.patreon.com/un1cum**

`Boosty`
* **Ссылка: https://boosty.to/un1cum**

`Крипта`


* ![BNB](https://user-images.githubusercontent.com/80776324/230691108-ecd10132-af58-4064-8c44-ad10f6f55dd1.png) **BNB: 0x96a0B6E4274771D5f3F8e59564b58C35D74D8Cc1**


* ![BTC](https://user-images.githubusercontent.com/80776324/230691099-1422c66c-099e-49f2-adee-b48fa9533c0c.png) **BTC: bc1qxfvstf99kyuc5x5uugxtsh3m6w3a73ruzfav7e**


* ![ETH](https://user-images.githubusercontent.com/80776324/230691090-32c937b9-61bc-4eeb-b058-c46c8fc250ac.png) **ETH: 0x96a0B6E4274771D5f3F8e59564b58C35D74D8Cc1**


* ![LTC](https://user-images.githubusercontent.com/80776324/230691072-c3bc7a2b-7e4e-4a4b-ab56-e82ee5ffb717.png) **LTC: ltc1qudx4ge8zvncqpdtl5mshfqjxzyvg43f27ysqjt**


* ![USDT](https://user-images.githubusercontent.com/80776324/230691044-44802059-c433-4de5-a221-0f69c0b7c660.png) **USDT (TRC-20): TKVs4Bt63mVGSYth7HSvNQBk8Xp1UKMH9Y**
