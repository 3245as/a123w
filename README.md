# [Arlux](https://telegram.me/Arlux)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh# Let's install the bot.
cd $HOME
git clone https://github.com/BeyondTeam/BDReborn.git
cd BDReborn
chmod +x beyond.sh
./beyond.sh install
./beyond.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```shcd $HOME && git clone https://github.com/BeyondTeam/BDReborn.git && cd BDReborn && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo And Bot
After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    157059515,
    0,
    YourID
  }
```
add your bot ID at line 4 and add your ID at line 87 in bot.lua
add your ID at line 2 in tools.lua
Then restart the bot.


* * *

### Our Telegram channel:

[@ArluxTeam](https://telegram.me/BeyondTeam)
