# LynxBot

A  advanced UserBot for Telegram Users. Based on Latest Telethon (1.21.1) and made using Latest Python (3.9.5). **Managed By :[@MoralBoy_xD](https://telegram.me/MoralBoy_xD).** 

<div class="separator" style="clear: both; text-align: center;">
<a href="https://te.legra.ph/file/05db5b237fb0a98d577bc.jpg" imageanchor="1" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="500" data-original-width="500" height="500" src="https://te.legra.ph/file/05db5b237fb0a98d577bc.jpg" width="500" /></a></div>

-------------------------------------------------

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f7c51539e67b483bb8d7749acca51d3a)](https://app.codacy.com/gh/TEAM-LYNX-OP/LYNX-BOT?utm_source=github.com&utm_medium=referral&utm_content=MadBoy-X/SuperBot&utm_campaign=Badge_Grade_Settings)

![GitHub Repo Size](https://img.shields.io/github/repo-size/TEAM-LYNX-OP/LYNX-BOT)

-------------------------------------------------

# Dᴇᴘʟᴏʏ:-

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new-app?template=https://github.com/TEAM-LYNX-OP/LYNX-BOT)

------------------------------------------------

# Sᴛʀɪɴɢ Sᴇssɪᴏɴ:-

## [String Session](https://t.me/SessionStringGeneratorZBot)

-------------------------------------------------

## The owner/devs won't be responsible for any kind of bans due to the bot...
## Fᴏʀᴋ Aᴛ Yᴏᴜʀ Oᴡɴ Rɪsᴋ

-------------------------------------------------

## Iɴsᴛᴀʟʟɪɴɢ (Nᴏʀᴍᴀʟ Wᴀʏ)

Simply clone the repository and run the main file:
```sh
git clone https://github.com/TEAM-LYNX-OP/LYNX-BOT
cd Lynx-Bot
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m Lynx-Bot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### Uɴɪʙᴏʀɢ Cᴏɴғɪɢʀɪᴜᴛɪᴏɴ

The UniBorg Config is situated in `LynxBot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
UnFortunately, there are no Mandatory vars for the UniBorg Support Config.

## Mᴀɴᴅᴀᴛᴏʀʏ Vᴀʀs

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org 
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The LynxBot will not work without setting the mandatory vars.

-------------------------------------------------

-------------------------------------------------


