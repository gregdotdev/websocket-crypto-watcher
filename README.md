# 📈 LTC Price Tracker (CLI Version)

```
 ▄████▄   ██▀███ ▓██   ██▓ ██▓███  ▄▄▄█████▓ ▒█████      █     █░ ▄▄▄     ▄▄▄█████▓ ▄████▄   ██░ ██ ▓█████  ██▀███  
▒██▀ ▀█  ▓██ ▒ ██▒▒██  ██▒▓██░  ██▒▓  ██▒ ▓▒▒██▒  ██▒   ▓█░ █ ░█░▒████▄   ▓  ██▒ ▓▒▒██▀ ▀█  ▓██░ ██▒▓█   ▀ ▓██ ▒ ██▒
▒▓█    ▄ ▓██ ░▄█ ▒ ▒██ ██░▓██░ ██▓▒▒ ▓██░ ▒░▒██░  ██▒   ▒█░ █ ░█ ▒██  ▀█▄ ▒ ▓██░ ▒░▒▓█    ▄ ▒██▀▀██░▒███   ▓██ ░▄█ ▒
▒▓▓▄ ▄██▒▒██▀▀█▄   ░ ▐██▓░▒██▄█▓▒ ▒░ ▓██▓ ░ ▒██   ██░   ░█░ █ ░█ ░██▄▄▄▄██░ ▓██▓ ░ ▒▓▓▄ ▄██▒░▓█ ░██ ▒▓█  ▄ ▒██▀▀█▄  
▒ ▓███▀ ░░██▓ ▒██▒ ░ ██▒▓░▒██▒ ░  ░  ▒██▒ ░ ░ ████▓▒░   ░░██▒██▓  ▓█   ▓██▒ ▒██▒ ░ ▒ ▓███▀ ░░▓█▒░██▓░▒████▒░██▓ ▒██▒
░ ░▒ ▒  ░░ ▒▓ ░▒▓░  ██▒▒▒ ▒▓▒░ ░  ░  ▒ ░░   ░ ▒░▒░▒░    ░ ▓░▒ ▒   ▒▒   ▓▒█░ ▒ ░░   ░ ░▒ ▒  ░ ▒ ░░▒░▒░░ ▒░ ░░ ▒▓ ░▒▓░
  ░  ▒     ░▒ ░ ▒░▓██ ░▒░ ░▒ ░         ░      ░ ▒ ▒░      ▒ ░ ░    ▒   ▒▒ ░   ░      ░  ▒    ▒ ░▒░ ░ ░ ░  ░  ░▒ ░ ▒░
░          ░░   ░ ▒ ▒ ░░  ░░         ░      ░ ░ ░ ▒       ░   ░    ░   ▒    ░      ░         ░  ░░ ░   ░     ░░   ░ 
░ ░         ░     ░ ░                           ░ ░         ░          ░  ░        ░ ░       ░  ░  ░   ░  ░   ░     
░                 ░ ░                                                              ░                                
```

> **CLI VERSION - v1**

---

## 💡 About

This is a simple CLI Tracker project that monitors the Litecoin (LTC) price in real time using the [Binance](https://www.binance.com/). WebSocket API. Every time the price changes, it’s instantly updated in the terminal.

---

## ⚙️ Requirements/Technologies used

- Python 3
- [websocket-client](https://pypi.org/project/websocket-client/)
- API WebSocket Binance

---

## 🧪 How to Install

1. Clone the repository:

```bash
git clone https://github.com/gregdotdev/websocket-crypto-watcher.git
cd websocket-crypto-watcher
```

2. Install the requirements:

```bash
pip install websocket-client
```

3. Execute the program:

```bash
python tracker.py
```

---

## 📺 Example of output

```
Currently watching: LTC
-------------------------------- 

Actual Price: R$358.24
```

---

## 📝 Código principal

The script connects to Binance’s trade WebSocket for the `ltcbrl@trade` pair and prints the real-time price whenever it changes.

---

## 📄 Licença

This projct is on the MIT License. See the archive [LICENSE](LICENSE) to more info.
