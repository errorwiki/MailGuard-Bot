# MailGuard-Bot


<h1 align="center"> Temporary Email Addresses MailGuard-Bot 💌</h1>

<p align="center">
<img src="https://generator.email/pages/blog/img/title/5.png" height="300">
</p>

<p align="center">
  <em>This is a Telegram bot script utilizing the mail.tm API. It allows users to generate temporary email addresses within Telegram, access their inbox, and read messages, all without leaving the app.</em>
</p>
<hr>

## Features

- Generate temporary email addresses.
- Check the inbox of the generated email.
- Read emails directly through Telegram.
- Supports custom username and password for email generation.
- Secure: your temporary emails and messages are private and accessible only to you.

## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.6 or higher.
- `requests` , `beautifulsoup4` and `aiogram==2.6` libraries.
- A Telegram bot token (you can get one from [@BotFather](https://t.me/BotFather) on Telegram).

## Installation

To install necessary utilities, run the following commands:

```bash
pip install beautifulsoup4
pip install aiogram==2.6
```

## Configuration

1. Open the script with your favorite text editor.
2. Find the line that contains `API_TOKEN = '123456:ABCDEFGHIJLLJOdMttZ5hEZ78'`.
3. Replace the placeholder token with your actual Telegram bot token.

## Deploy the Bot

```sh
git clone https://github.com/errorwiki/MailGuard-Bot
cd TempMail-Bot
python3 tempmail.py
```

## Bot Commands

- `/tmail` - Command for Generate Random Mail with Pass
- `/tmail [username]:[password]` - Generate a temporary email. with a specify a username and password.
- `/cmail <token>` - Check the inbox of your temporary email by providing the token received during email generation.

✨ **Note**: When you generate a mail pass, then you will receive a mail token. With the token, you can check 10 recent mails, each mail has a different token, so keep it privately. The mail generator general quota limit is 8 queries per second (QPS) per IP address.

## Author

- Name: Vikas Yadav
- Instagram: [@thewikiii](https://instagram.com/thewikiii)

Feel free to reach out if you have any questions or feedback.
