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
# Интерактивный справочник по командам Linux

def show_help():
    print("\n--- Шпаргалка по Linux для QA и ИБ ---")
    print("1. Как посмотреть, что лежит в папке?")
    print("2. Как узнать текущую версию Apache/сервиса?")
    print("3. Как проверить сетевое соединение (пинг)?")
    print("4. Выход")

while True:
    show_help()
    choice = input("\nВыбери номер вопроса (1-4): ")

    if choice == "1":
        print("\n💡 Ответ: Используй команду 'ls' (или 'ls -la' для скрытых файлов).")
    elif choice == "2":
        print("\n💡 Ответ: Команда 'nmap -sV [IP-адрес]' покажет версии всех запущенных служб.")
    elif choice == "3":
        print("\n💡 Ответ: Используй команду 'ping [IP-адрес или сайт]'.")
    elif choice == "4":
        print("\nОтличная работа сегодня! До встречи.")
        break
    else:
        print("\n❌ Неверный ввод, выбери число от 1 до 4.")
C:\Users\dimam\PyCharmMiscProject\.venv\Scripts\python.exe C:\Users\dimam\PyCharmMiscProject\script.py 

--- Шпаргалка по Linux для QA и ИБ ---
1. Как посмотреть, что лежит в папке?
2. Как узнать текущую версию Apache/сервиса?
3. Как проверить сетевое соединение (пинг)?
4. Выход

Выбери номер вопроса (1-4): 
