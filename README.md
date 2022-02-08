# TG-videoCompress

A Telegram Bot To Encode Videos Using FFMPEG.

- `Queue` - This bot has queue feature.
- `Thumbnail` - Send any image and it will be set as file thumbnail.
- `OWNER` - Only authorised user can use it.
- `FFMPEG Code Change` - Change ffmpegcode through the bot itself do /help in bot pm for more info.

## Deploy On

`Heroku`

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Anshusharma75/TG-videoCompress)

`Railway` 

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FAnshusharma75%2FTG-videoCompress&envs=API_HASH%2CAPP_ID%2CBOT_TOKEN%2COWNER%2CTHUMBNAIL&optionalEnvs=THUMBNAIL&API_HASHDesc=Get+this+value+from+telegram.org+&APP_IDDesc=Get+this+value+from+telegram.org+&BOT_TOKENDesc=Go+to+%40Botfather+and+make+a+new+bot+and+paste+the+bot+token+here&OWNERDesc=Your+owner+Id+%28add+only+1+id+for+working+queue+feature+%29&THUMBNAILDesc=Add+thumbnail+telegraph+link+&THUMBNAILDefault=https://telegra.ph/file/3b88ebb3aa3f54caa0aea.jpg)


- [Original Repo](https://github.com/1Danish-00/CompressorQueue)

## Commands
Add in [@BotFather](https://t.me/BotFather)

    start - Check Bot is Working or not
    help - Get Detailed Help
    setcode - Set Custom FFMPEG Code
    getcode - Print Current FFMPEG Code
    logs - Get Bot Logs
    ping - Check Ping
    sysinfo - Get System Info
    renew - Clear Cached Downloads, Queue etc
    clear - Clear Queued Files
    showthumb - Show Current Thumbnail
    cmds - List Available Commands

 
## Variables 

variables for indirectly deployment.

- `APP_ID` - Api ID of Owner (get it from [my.telegram.org](my.telegram.org).
- `API_HASH` - Api hash of Owner (get it from [my.telegram.org](my.telegram.org).
- `OWNER` - Put Id Of Auth Users with a space between it, Those are able to use bot.
- `THUMBNAIL` - Your custom Thumbnail you can also change it in your bot PM.
