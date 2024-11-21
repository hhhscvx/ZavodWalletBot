[<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/hhhscvx)


## Functionality
| Functional                                                     | Supported |
|----------------------------------------------------------------|:---------:|
| Multithreading                                                 |     ✅     |
| Binding a proxy to a session                                   |     ✅     |
| Auto Claiming                                                  |     ✅     |
| Random sleep time between claim                                |     ✅     |
| Auto upgrade                        y                           |     ✅     |

## [Change Settings](https://github.com/hhhscvx/ZavodWalletBot/blob/master/bot/config/config.py)
| Настройка                | Описание                                                                               |
|--------------------------|----------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Platform data from which to launch a Telegram session (stock - Android)                |

## Installation
You can download [**Repository**](https://github.com/hhhscvx/ZavodWalletBot) by cloning it to your system and installing the necessary dependencies:
```shell
~ >>> git clone https://github.com/hhhscvx/ZavodWalletBot.git
~ >>> cd ZavodWalletBot

#Linux
~/ZavodWalletBot >>> python3 -m venv venv
~/ZavodWalletBot >>> source venv/bin/activate
~/ZavodWalletBot >>> pip3 install -r requirements.txt
~/ZavodWalletBot >>> cp .env-example .env
~/ZavodWalletBot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/ZavodWalletBot >>> python3 main.py

#Windows
~/ZavodWalletBot >>> python -m venv venv
~/ZavodWalletBot >>> venv\Scripts\activate
~/ZavodWalletBot >>> pip install -r requirements.txt
~/ZavodWalletBot >>> copy .env-example .env
~/ZavodWalletBot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/ZavodWalletBot >>> python main.py
```