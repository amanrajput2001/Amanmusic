<p align="center"><a href="http://t.me/Aman_vstreamingbot"><img src="https://github.com/amanrajput2001/Amanmusic/blob/main/etc/aman.png"></a></p>
<p align="center">
    <br><b>Veez Music is a telegram bot project that's allow you to play music on telegram voice chat group</b><br>
</p>


<h3>Requirements 📝</h3>

- FFmpeg
- NodeJS [deb.nodesource.com](https://deb.nodesource.com/)
- Python 3.8 or higher
- [MongoDB](https://cloud.mongodb.com/)
- [2nd Telegram Account](https://telegram.org/blog/themes-accounts#multiple-accounts) (needed for userbot)

### 🧪 Get `SESSION_NAME` from below:

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/StringSession#main.py) ``Pyrogram``

### 🎖 History

[![Mentioned in Awesome Python](https://awesome.re/mentioned-badge.svg)](https://github.com/amanrajput2001/Amanmusic)

## Features 🔮

- Thumbnail Support
- Playlist Support
- Youtube, Local playback support
- Settings panel
- Control with buttons
- Userbot auto join
- Keyboard selection support for youtube play
- Lyrics Scrapper
- Unlimited Queue
- Broadcast Bot
- Statistic Collector
- Block / Unblock (restrict user for using your bot)

## Commands 🛠

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/vsong <song name>` - download videos you want quickly
- `/lyric <song name>` - lyrics scrapper

#### Admins Only 👷‍♂️
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/music on` - to disable music player in your group
- `/music off` - to enable music player in your group
- `/join` - invite assistant to your chat
- `/leave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status
- `/auth` - authorized people to access the admin commands
- `/unauth` - deauthorized people to access the admin commands
- `/control` - open the music player control panel

### Sudo User 🧙‍♂️
- `/stats` - see the bot statistic
- `/leaveall` - order the assistant to leave all groups
- `/eval (query)` - execute any code
- `/sh (query)` - run any code

### Owner Only 👨🏻‍✈️
- `/broadcast` - send a broadcast message from the bot
- `/block` - block people for using your bot
- `/unblock` - unblock people you blocked for using your bot
- `/blocklist` - show the list of all people who's blocked for using your bot

## 🔎 Inline Search Support
- just type the bot username in any chat, example: "`@aman_vstreamingbot Faded Alan Walker`", then bot will give you a results of the query you search in inline mode.

## Heroku Deployment <img src="./etc/Kenpurple.gif" width="40px">
The easy way to host this bot, deploy to Heroku, Change the app country to Europe (it will help to make the bot stable).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/amanrajput2001/Amanmusic)

## VPS Deployment 📡

```sh
sudo apt update && apt upgrade -y
sudo apt install python3-pip ffmpeg -y
sudo curl -sL https://deb.nodesource.com/setup_17.x | sudo bash -
sudo apt-get install -y nodejs
sudo npm i -g npm
git clone https://github.com/levina-lab/VeezMusic # clone the repo.
cd VeezMusic
sudo pip3 install --upgrade pip
sudo pip3 install -U -r requirements.txt
cp example.env .env # use vim to edit ENVs
vim .env # fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
sudo python3 main.py # run the bot.
```

### Special Credits 💖
LOL BC KISI KO CREDIT NA MILEGA😂😂

### Support & Updates 🎑
<a href="https://t.me/india_chat_002"><img src="https://img.shields.io/badge/Join-Group%20Support-blue.svg?style=for-the-badge&logo=Telegram"></a> <a href="https://t.me/india_chat_002"><img src="https://img.shields.io/badge/Join-Updates%20Channel-blue.svg?style=for-the-badge&logo=Telegram"></a>
