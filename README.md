# Telegram Checkers Bot

This is a Telegram bot for playing checkers, either with a friend or against the computer. The bot is implemented using `PyTelegramBotAPI` and provides various difficulty levels when playing against the computer.

## Important Notes

1. **Database Requirement**:  
   You need to add a **database** to the bot for storing game data.  
   Without a database, the bot only works for one person with a PC or for two people playing against each other in the same session.  
   By adding a database, you will allow multiple users to play simultaneously without any issues.

2. **Bot Configuration (`config.py`)**:  
   The `config.py` file contains only one important variable — the bot's **token**.
   To make the bot work, simply insert your bot token into the `TOKEN` variable in `config.py`:

   ```python
   TOKEN = 'your-telegram-bot-token-here'
