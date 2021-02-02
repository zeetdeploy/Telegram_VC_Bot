# Telegram Voice-Chat Bot

Telegram Voice-Chat Bot To Play Music From Various Sources In Your Group

<img src="https://i.imgur.com/8S8NVy0.png" width="530" height="400">


# Support

1. All linux based os.
2. Windows
3. Mac

# Diagram

<img src="etc/scheme.png" width="919" height="448">

## Requirements

- Python 3.6 or higher
- A [Telegram bot token](//t.me/botfather)
- Bot needs to be admin in the chat, atleast give message delete permissions.
- Install `mpv` with

`pkg install mpv` - for Android,  `sudo apt-get install mpv` - for ubuntu, `sudo pacman -S mpv `  - for ArchLinux, I use arch btw
- For Windows Download mpv from https://sourceforge.net/projects/mpv-player-windows/files/ and run Mpv-installer as administrator the add mpv file to path envionment!

## Run

1. `git clone https://github.com/thehamkercat/Telegram_VC_Bot vbot && cd vbot`, to download the source code.
3. `pip3 install -r requirements.txt`, to install the requirements.
4. `cp sample_config.py config.py`
5.  sudo nano config.py
6. Download Telegram desktop from https://desktop.telegram.org , Log in using your second account, and connect to the voice chat in your group.
8. Run ` bash s.sh `
9. Run the bot `python3 main.py`
10. Open Telegram and start voice chat.
11. Send commands in group chat to play.

## Commands
Command | Description
:--- | :---
/start | To Start The bot.
/help | To Show This Message.
/ping | To Ping All Datacenters Of Telegram.
/end | To Stop Any Playing Music (only works for current user playing and to Admins).
/jiosaavn <song_name> | To Play A Song From Jiosaavn.
/youtube <song_name> or <song_link> | To Search For A Song And Play The Top-Most Song Or Play With A Link.
/playlist <youtube_playlist_url> | To Play A Playlist From Youtube.
/telegram | To Play A Song Directly From Telegram File.
/radio | To Play Radio Continuosly.
/users | To Get A List Of Blacklisted Users.
/deezer | To Play A Song From Deezer.
Admin Commands:
/black | To Blacklist A User.
/white | To Whitelist A User.

## Note

1. More services will be added soon.
2. Termux is not completely supported yet, might take a week or two.

## Credits
1. `https://github.com/cyberboysumanjay/JioSaavnAPI` [For JioSaavnAPI]
2. t.me/thehamkercat
