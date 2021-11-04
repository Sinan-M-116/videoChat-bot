
# Telegram Video Player Bot [![Mentioned by sinzzBotz ](https://awesome.re/mentioned-badge-flat.svg)]

An Telegram Bot By [@sinzzbotz](https://t.me/sinzzbotz) To Stream Videos in Telegram Voice Chat.

## Main Features

- Supports Live Streaming.

- Supports YouTube Streaming.

- Supports Live Radio Streaming.

- Supports Video Files Streaming.

- Supports YouTube Live Streaming.

- User Account Protection (PM Guard)

## Deploy Own Bot

### Heroku (Don't Complain)

<p><a href="https://heroku.com/deploy?template=https://github.com/Sinan-M-116/videoChat-bot"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>

## Commands (Set In Botfather)

```sh

start - Start The Bot

help - Show Help Message

play - Start Audio Streaming

stream - Start Video Streaming

pause - Pause The Current Stream

resume - Resume The Paused Stream

endstream - Stop Streaming & Left VC

```

## Config Vars

1. `API_ID` : User Account Telegram API_ID, get it from my.telegram.org

2. `API_HASH` : User Account Telegram API_HASH, get it from my.telegram.org

3. `BOT_TOKEN` : Your Telegram Bot Token, get it from @Botfather 

4. `SESSION_STRING` : Pyrogram Session String of User Account, 

5. `ASSISTANT_NAME` : Your Video Player's assistant username without @.

6. `SUPPORT_GROUP` : Support Group username without @ [Leave this if you don't have one]

7. `UPDATES_CHANNEL` : Updates Channel username without @ [Leave this if you don't have one]

8. `SUDO_USERS` : ID of Users who can use Admins commands (for multiple users seperated by space)

9. `REPLY_MESSAGE` : A reply to those who message the USER account in PM. Leave it blank if you do not need this feature.
