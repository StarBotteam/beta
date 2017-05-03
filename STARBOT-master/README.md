# [StarBot](https://telegram.me/SBT_RoBot)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/starbotteam/beta.git
cd beta
chmod +x STARBOT.sh
chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh
./STARBOT.sh install
./STARBOT.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/starbotteam/beta.git && cd STARBOT && chmod +x STARBOT.sh && chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh && ./STARBOT.sh install && ./STARBOT.sh
```

* * *

### launch Bot

```
killall screen
cd STARBOT && screen ./STARBOT.sh
```

* * *


### auto launch 
```
killall screen
cd MaTaDoR && screen ./auto.sh
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
