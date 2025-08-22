# Today's History-WhatsApp-Bot
You know what happened today in History?
# History Facts WhatsApp Bot

This bot sends **3 unique history facts every day at 9:00 AM IST** to all subscribers on WhatsApp.

## Features
- Uses Wikipedia "On This Day" API
- Stores facts in SQLite (no repeats)
- Sends via WhatsApp Business Cloud API
- Simple subscribe system ("send 'subscribe'" to join)

## Setup
1. Clone repo
2. Install dependencies: `pip install -r requirements.txt`
3. Copy `.env.example` → `.env` and fill values
4. Run: `python app.py`
5. Deploy on Heroku/Render

## WhatsApp Template
Name: `history_facts`  
Body:
