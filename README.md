# My First Discord Bot
This python project give you the necessary tools to write your own Discord bot in python.

I used `Python 3.12.6`.

## .env
To be able to use this exemple bot, you'll need a `.env` file.
```env
BOT_TOKEN=Your_Discord_Bot_Token
GUILD_ID=The_Discord_Server_Id
```

> [!note]
> ### How to get your Bot token ?
> To get your bot token, you'll need to go to the [Discord Developer Portal](https://discord.com/developers/applications).
> You'll have to create a `New Application` and in the `Bot` page, you'll have to:
> - Turn on `Presence Intent`
> - Turn on `Server Members Intent`
> - Turn on `Message Content Intent`
> - Check `Administartor` in the `Bot Permissions` that way the bot can do anything. _(Make sure to trust the code)_
> 
> Then on the `OAuth2` page, in the `OAuth2 URL Generator` part, check `bot`, copy the url and pasted it in your browser.
> 
> Once your bot on the server you wanted it to be, back on the `Discrod Developer Portal`, in the `Bot` page, you'll find a button `Reset Token`. Click on it and then your token will be displayed. __Make sure to save it, it'll be showed one time only__.

> [!note]
> ### How to get the ID of your Server ?
> On Discord, you'll have to go to your `user settings` and in the `Advanced` tab. In there, you'll have to turn on the `Developer Mode`.
>
> Then make a right click on the server you want the bot in and at the bottom of the context menu, you'll find the possibility to copy the ID of the server.

## Dependencies
This project use:
- discord.py
- python-dotenv
