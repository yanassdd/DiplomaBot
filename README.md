Опис проекту
Rhythm of Life Bot — це Telegram-бот для планування завдань і звичок з можливiстю інтеграцiї з Google Calendar. 
Бот допомагає створювати звички, завдання, нагадувати про них і аналiзувати ваш прогрес.

Функцiї бота
- Створення звичок зі вибором днів тижня і нагадувань.
- Створення завдань з дедлайном та нагадуванням.
- Автоматичне нагадування про завдання та звички.
- Редагування і видалення завдань/звичок.
- Статистика і графiки прогресу.
- Інтеграцiя з Google Calendar з особистою авторизацiєю.
- Автоматичне видалення прострочених завдань.
- Вибiр користувачем, чи додавати завдання в Google Calendar.

Технічні деталі
- Python 3.12
- PostgreSQL (зберiгання даних)
- TeleBot (pyTelegramBotAPI)
- Matplotlib (графiки)
- Google API Client (інтеграцiя з календарем)
- OAuth 2.0 авторизацiя

Встановлення
1. Клонувати репозиторiй:
git clone <url>
2. Встановити залежностi:
pip install -r requirements.txt
3. Заповнити файл .env:
API_TOKEN=<Telegram Bot Token>
DB_HOST=localhost
DB_PORT=5432
DB_NAME=telegram_bot_db
DB_USER=botuser
DB_PASSWORD=<password>
4. Зареєструвати Google API Project, отримати credentials.json.
5. Запусти бота:
python main.py
