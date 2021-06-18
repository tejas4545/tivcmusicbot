<h1 align="centre">TI VC Music Bot</h1>

### A bot that can play music on Telegram Group and Channel Voice Chats

<p align="center">
  <a href="https://github.com/tejas4545/tivcmusicbot">
     <img height="30px" src="https://img.shields.io/badge/Group%20Music%20Bot-red?style=for-the-badge&logo=github">
  </a>
</p>

<p align="center">
  <a href="https://telegra.ph/file/08b5c954d7f723d0ad454.jpg">
     <img height="150px" src="https://telegra.ph/file/08b5c954d7f723d0ad454.jpg">
  </a>
</p>


### Deploy To Heroku 📡</h4>

<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/tejas4545/tivcmusicbot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="210" height="34.45"/></a></p>



### Features✨Cancel changes

- Thumbnail Support
- Playlist Support
- Current playback support
- Showing track names when skipping
- Zero downtime, Fully Stable
- DEEZER,YOUTUBE & SAAVN PLAYBACK SUPPORTED
- Settings panel
- Control with buttons
- Userbot auto join
- Channel Music Play
### Requirements 📝

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.7+
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

### ⚔ Self-hosting (For Devs) 
```sh
# Install Git First (apt-instll git)
$ git clone https://github.com/tejas4545/tivcmusicbot
$ cd GroupMusicBot
# Upgrade sources
# Install All Requirements 
$ pip(3) install -r requirements.txt
# Rename example.env to local.env and fill
$ npm i -g npm
# Start Bot 
$ python(3) -m MusicBot
```

### Commands for Group 🛠
#### For all in group

- `/play <song name>` - play song you requested
- `/play <reply to audio>` - play replied file
- `/dplay <song name>` - play song you requested via deezer
- `/splay <song name>` - play song you requested via jio saavn
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/deezer <song name>` - download songs you want quickly via deezer
- `/saavn <song name>` - download songs you want quickly via saavn
- `/video <song name>` - download videos you want quickly

#### Admins only.
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/reload` - Refresh admin list

### Commands for Channel Music Play 🛠
For linked group admins only:
- `/cplay <song name>` - play song you requested
- `/cplay <reply to audio>` - play replied file
- `/cdplay <song name>` - play song you requested via deezer
- `/csplay <song name>` - play song you requested via jio saavn
- `/cplaylist` - Show now playing list
- `/cccurrent` - Show now playing
- `/cplayer` - open music player settings panel
- `/cpause` - pause song play
- `/cresume` - resume song play
- `/cskip` - play next song
- `/cend` - stop music play
- `/userbotjoinchannel` - invite assistant to your chat

### Commands for Sudo Users ⚔️
- `/userbotleaveall` - remove assistant from all chats
- `/gcast <reply to message>` - globally brodcast replied message to all chats
- `/pmpermit [on/off]` - enable/disable pmpermit message

#### Pmpermit
- `.a` - approove someone to pm you
- `.da` - disapproove someone to pm you
+ Sudo Users can execute any command in any groups
