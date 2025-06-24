# 🚀 [Wi-Fi Jammer](https://github.com/Artemy-dev/Wi-Fi-Jammer) — ARP Flood Tool for Network Testing  
A Python CLI script that performs ARP flood attacks to simulate Wi-Fi jamming and test ARP-related vulnerabilities.  
(Скрипт для ARP-флуд атаки с целью временного «глушения» Wi-Fi — используется для тестирования сетевой безопасности.)

---

## 💻 Supported Platforms

- ✅ Linux  
- ✅ macOS  
- ✅ Windows (WSL / с ограничениями)

---

## 📦 Features / Возможности

- 🔹 Sends spoofed ARP responses to all hosts in the subnet (Рассылает поддельные ARP-ответы всем устройствам в подсети)
- 🔹 Breaks connectivity between clients and router (Нарушает связь между клиентами и роутером)
- 🔹 Built with [Scapy](https://scapy.net/) — no extra tools required (Работает только через Python + Scapy)

---

## ❓ Why this project? / Зачем этот проект?

This tool was created for educational and audit purposes — to demonstrate how simple ARP-based denial of service attacks work and help test local network resilience<br>  
Проект предназначен для демонстрации уязвимостей ARP и проверки устойчивости локальных сетей. Использовать **только в разрешённых сетях!**

---

## 🚀 Installation / Установка

```bash
git clone https://github.com/Artemy-dev/Wi-Fi-Jammer.git
cd Wi-Fi-Jammer
pip install scapy
````

---

## ⚙️ Usage / Пример использования

> Requires root/admin privileges
> Требуются права администратора (root)

```bash
sudo python3 main.py --iface <interface> --gateway-ip <IP> --gateway-mac <MAC>
```

**Example / Пример:**

```bash
sudo python3 main.py --iface en0 --gateway-ip 192.168.0.1 --gateway-mac c8:3a:35:28:3e:78
```

---

## 📁 Project Structure / Структура проекта

```
├── main.py
├── README.md
└── requirements.txt
```

---

## 👤 Author / Автор

**Artem Grachev**<br>
Python/Golang Developer | ML & DevOps Enthusiast<br>
🇷🇺 Telegram: [@Artemy\_Develop](https://t.me/Artemy_Develop)<br>
🌐 GitHub: [Artemy-dev](https://github.com/Artemy-dev)

---

## 🌍 SEO Keywords

* wifi jammer
* arp flood attack
* python arp spoof
* network denial of service
* scapy network tool
* arp poison script
* cli wifi attack python
* simulate arp spoofing
* ethical hacking tools
* python network test
