# My QA & Cybersecurity Journey 🚀

Добро пожаловать в мой личный репозиторий! Здесь я собираю отчеты, практические кейсы и результаты своего обучения.

## 🛠️ Технологический стек & Инструменты
* Languages: Python (в процессе изучения)
* API Testing: Postman
* OS: Linux
* Platforms: TryHackMe

## 📈 Мои достижения (TryHackMe)
* Guided Pentest: Web — Успешно пройден этап *Reconnaissance and Enumeration* (сбор информации, определение версий Apache и MySQL).

---
*Двигаюсь по четкому плану от простого к сложному.*
# -*- coding: utf-8 -*-
# Интерактивный справочник по Linux для пентестинга

def show_help():
    print("\n🛡️ Справочник Linux для Pentest")
    print("1. Разведка (Recon)")
    print("2. Сканирование портов")
    print("3. Поиск директорий")
    print("4. Тестирование веб‑уязвимостей")
    print("5. Сниффинг и перехват")
    print("6. Выход")

help_dict = {
    "1": "Разведка:\n- whois [домен]\n- dig [домен]\n- nslookup [домен]\n- theHarvester -d [домен] -b all",
    "2": "Сканирование портов:\n- nmap -sV -sC [IP]\n- nmap -p- [IP]\n- rustscan -a [IP]",
    "3": "Поиск директорий:\n- gobuster dir -u http://site -w /usr/share/wordlists/dirb/common.txt\n- dirsearch -u http://site",
    "4": "Веб‑уязвимости:\n- sqlmap -u 'URL?id=1' --batch\n- nikto -h http://site\n- curl -I http://site",
    "5": "Сниффинг:\n- tcpdump -i eth0\n- wireshark\n- tshark -i wlan0",
}

while True:
    show_help()
    choice = input("\n🔹 Выбери номер раздела: ")

    if not choice.isdigit():
        print("\n❌ Введи число, а не текст.")
        continue

    if choice == "6":
        print("\n👋 Выход из справочника.")
        break

    print("\n📌", help_dict.get(choice, "Неверный ввод, попробуй снова."))
