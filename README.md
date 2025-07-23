# 🤖 Telegram Echo Bot with Username Tracker

This is a simple Telegram bot built using the `python-telegram-bot` library. It greets users, responds to basic messages, and keeps track of usernames by saving them into a local `usernames.json` file.

---

## 🚀 Features

- Greets users with `/start`
- Replies with a help message on `/help`
- Echoes any text messages sent to the bot
- Special responses for:
  - `hello` → `hello`
  - `good bye` → `goodbye`
- Saves every unique username to `usernames.json`

---

## 🧠 How It Works

When a user interacts with the bot:
- Their Telegram username is checked.
- If it's new, it's saved into `usernames.json`.
- Depending on the command or message, the bot replies accordingly.


---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/telegram-echo-bot.git
cd telegram-echo-bot


---

## 📦 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/telegram-echo-bot.git
cd telegram-echo-bot

pip install -r requirements.txt

application = Application.builder().token("YOUR BOT TOKEN").build()
