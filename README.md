
> MassDM v3, a bot to send mass DM's to members of a Discord server.



**To use MassDM v3, you will need to know a few things.**

1. I do not guarantee that your Discord account will not get banned and I do not guarantee that this bot will work.
2. DO NOT use this on your main account under any cirumstances.
3. Always use a VPN or a proxy as you may get IP banned.



You will need two things installed to make this bot work.

- Node.JS(LTS version). https://nodejs.org/en/
- A code editor. https://notepad-plus-plus.org/

Open `config.json` in your code editor and edit the token with your bot token or your user token.
You also need to add in your whitelisted ID. The ID of the user who will control the bot.
Once you have that done, save the file.
*Alternatively, you can pass in the token through an enviornment variable named `BOT_TOKEN`*

Run `install_dep.bat` if you are on Windows.
Otherwise you need to open a terminal in the bot folder and type "npm install -d" without quotes.

Once it has finished installing all the dependencies, you can run `start.bat`.
*If you are not running Windows, you need to open a terminal in the bot folder and type "node app.js" without quotes.*



Ideas for development:
- [x] env var token
- [ ] customize bot status