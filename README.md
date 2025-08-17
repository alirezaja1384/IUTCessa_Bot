# IUTCessa Bot — Telegram Bot for IUT Computer Engineering Student Scientific Association 🛠🤖

**IUTCessa Bot** is a Telegram bot specifically designed for the Computer Engineering Department at Isfahan University of Technology (IUT), under the supervision of the IUT Computer Engineering Student Scientific Association (IUTCessa).

---

## 🚀 Goal

Its primary goal is to establish a management and automation system for various association initiatives, such as:

* **Kmkyar** — a program to help with volunteer assistance program 🤝
* **Tech-Stack Mentoring Courses** — Tech Stack mentoring courses 📚

---

## 🧩 Main Parts

* **Tech Stack (`techstack`)** — handles key tasks including launching registration panels, sending general or targeted notifications, managing priority selection panels, database administration, and overseeing payment receipts. (Both user and admin panels)
* **Volunteer Program (`kmkyar`)** — apply to help, and get links for the selected group.

---

## 🤖 AI Helper (v1.3.0+)

A new AI part (run by the Gemma model) was added and is still being worked on. It can now:

* **TL;DR / sum up** — make long texts short and easy to get.
* **Ask / chat mode** — ask the bot things and talk to it in simple words.

> Note: the AI helper is still being tested and changed — look for more and better parts.

---

## ⚙️ Setting It Up

To set up the bot, change the `core/token.py` file in the way you want.
All main tokens, bot tokens, and group IDs are in there with short notes on each. For more hard tasks, you can find and change extra settings in `core/CommandFunctions.py`.

---

## 🛠 How to begin (fast)

1. Get the copy:
   `git clone https://github.com/Nec-ro/IUTCessa_Bot.git`
2. Make and start a Python space just for this.
3. Add what's needed:
   `pip install -r requirements.txt`
   (`python-telegram-bot==22.1 openai`)
4. Change `core/token.py` and `core/CommandFunctions.py` with your bot token and group IDs.
5. Start the bot:
   `python main.py` (or the start file for the project)

*(Make sure commands fit the repo’s real start point if different.)*

---

## 🧾 Issues & Adding Your Part

This project is **free to use** — we like help, bug reports, and ideas for new stuff!
If you face any issues, please start an **Issue** on the GitHub page. We welcome pull requests — from small fixes to big new things. 🙌

---

## 📎 Start Editing Here

* `core/token.py` — main setup (tokens, group IDs).
* `core/CommandFunctions.py` — hard command setup and parts you might change.
* `core/` — other main parts and helpers for how the bot acts and its data handling.

---

## ❤️ Ending Words

This bot was made (with love 💖) to help the IUT Computer Engineering group work better and cut down on admin work. If you need help fitting it to your server, adding stuff, or using a new AI part, I’m here to help — and we would love your help on this project! 👨‍💻👩‍💻