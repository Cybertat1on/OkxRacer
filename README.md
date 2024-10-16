[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/OKX_official_bot/OKX_Racer?startapp=linkCode_96698625)
[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/CyberToolz)

#  Bot for OkxRacer

# 🔥🔥 PYTHON version must be 3.10 - 3.11.5 🔥🔥

> 🇷 🇺 README in russian available [[here](https://github.com/Cybertat1on/OkxRacer/blob/main/README-RU.md)]

## Features  
| Feature                          | Supported |
|----------------------------------|:---------:|
| Multithreading                   |     ✅     |
| Proxy binding to session         |     ✅     |
| Support for  pyrogram .session   |     ✅     |
| Auto-farming                     |     ✅     |
| Auto-tasks (except KYC)          |     ✅     |
| Auto-boost                       |     ✅     |
| Auto-daily                       |     ✅     |


## [Settings](https://github.com/Cybertat1on/OkxRacer/blob/master/.env-example/)
| Settings                |                                 Description                                 |
|-------------------------|:---------------------------------------------------------------------------:|
| **API_ID / API_HASH**   | Platform data from which to run the Telegram session (by default - android) |
| **SLEEP_TIME**          |             Sleep time between cycles (by default - [300, 500])             |
| **FUEL_TANK_BOOST**     |                 Buying Fuel «Tank boost» (by default - True)                 |
| **RELOAD_TANK_BOOST**   |                Buying Reload «Tank boost» (by default - True)                |
| **TURBO_CHARGER_BOOST** |               Buying Turbo «Charger boost» (by default - True)               |
| **AUTO_TASK**           |                Auto tasks (except KYC task) (default - True)                |
| **REF_ID**              |                                Referral link                                |
| **RANDOM_PREDICTION**   |                Using random for prediction (default - True)                 |
| **MAX_COMBO_COUNT**     |                       Max combo count (default - 28)                        |
| **USE_PROXY_FROM_FILE** | Whether to use a proxy from the bot/config/proxies.txt file (True / False)  |

## Quick Start 📚

To fast install libraries and run bot - open `run.bat` on **Windows** or `run.sh` on **Linux**

## Prerequisites
Before you begin, make sure you have the following installed:
- [**Python**](https://www.python.org/downloads/release/python-3100/) **version 3.10**

## Obtaining API Keys
1. Go to [**my.telegram.org**](https://my.telegram.org/auth) and log in using your phone number.
2. Select `API development tools` and fill out the form to register a new application.
3. Record the `API_ID` and `API_HASH` provided after registering your application in the `.env` file.

## Installation
You can download the [**repository**](https://github.com/Cybertat1on/OkxRacer) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/Cybertat1on/OkxRacer.git
cd OkxRacer
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
sudo sh install.sh
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/OkxRacer >>> python3 main.py --action (1/2)
# Or
~/OkxRacer >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/OkxRacer >>> python main.py --action (1/2)
# Or
~/OkxRacer >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```
