# Set Up
This will contain all the basic files you need!

# Setup
To setup this bot you must first have a discord application created. For this go to [discord.dev](https://discord.com/developers/applications) in your browser. From there click on "New Application" and give it a name! From there navigate to the "Bot" tab and click on "Copy Token" If this isnt your first time making a bot it may ask you to "Reset Token".

One you have got your token navigate to your .env.example file and change `TOKEN = Your Token Here` to your bots token. 
Make sure not to share your token as this allows anyone to control your bot.

After this all you have to do is run `npm i discord.js` in the console. 
If you are unsure on how to open the console click ` or the button above your tab key.

After all of this you can run your bot by simple typing `node index.js`

# Edit `index.js`
To get your bot to respond to you when you @ it replace `if (message.content === '<@1260993478708428901>')` with `if (message.content === '<@Your Application ID>')`
To find your applications ID go to [discord.dev](https://discord.com/developers/applications), select your bot and under General Information you should find something like "APPLICATION ID" followed by a random string of numbers. For example mine is 1260993478708428901. Edit Your Application ID with your application ID

# Errors
If you get an error such as `Error: Used disallowed intents` Go to your bot tab in [discord.dev](https://discord.com/developers/applications) and find where it says "Privileged Gateway Intents". If you are using an unverified bot I recomend selecting all and then saving. If you bot in verifed however. You will haev to apply for gateway intents.