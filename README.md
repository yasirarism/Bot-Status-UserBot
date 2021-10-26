# Bot-Status-UserBot

A telegram bot status checking userbot for bot updates channel's admins.

---

## Deploy 

<details>
  <summary><b>Deploy on Heroku</b></summary>
<br/>

<p align="left">
  <a href="https://heroku.com/deploy?template=https://github.com/FayasNoushad/Bot-Status-UserBot/tree/main">
     <img height="30px" src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku">
  </a>
</p>

</details>

<details>
  <summary><b>Deploy in your vps</b></summary>
<br/>

```sh

git clone https://github.com/FayasNoushad/Bot-Status-UserBot/tree/main
cd Bot-Status-UserBot
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 main.py
```

</details>

---

## Variables

- `SESSION_STRING` Owner pyrogram session string
- `API_ID` From my.telegram.org
- `API_HASH` From my.telegram.org
- `BOTS` Bots usernames with a space ( Like :- `BotFather Like Donate`)
- `BOT_OWNER` Owner ID 
- `UPDATE_CHANNEL` Channel of editing message 
- `MESSAGE_ID` ID of editing message
- `TIME_LIMIT` Time limit for checking bots one by one
- `SLEEP_TIME` Time limit for sleeping after checking bots
- `HEADING` Heading of the message 
- `ATTACH_LINK` Attach link for message

---

## Credits

- Full credits goes to [Christy Roys](https://github.com/odysseusmax) for his [Bot Status UserBot](https://github.com/odysseusmax/bug-free-broccoli)
- Updated / Modified by [FayasNoushad](https://github.com/FayasNoushad)

---
