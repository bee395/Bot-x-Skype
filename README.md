# Bot-x-Skype

[Skype bot](https://join.skype.com/bot/afb948bf-44b2-43a7-b061-609d4e61799c?add) built with node.js and MS Bot Framework

# Run it locally

 - Register a new bot at [https://dev.botframework.com/](https://dev.botframework.com/)
 - Generate app id and app password
 - Supply app id and app password to <code>ChatConnector</code> at lines **13** and **14** respectively of app.js
 - Download the project and run <code>npm install</code> in the terminal at the directory root level
 - Run <code>node app.js</code> at the root level directory
 - Download [ngrok](https://ngrok.com) and run <code>ngrok.exe</code> from the extracted folder
 - Run <code>ngrok http 8080</code> at this ngrok terminal
 - Copy the secure (https) link and paste it to **Messaging endpoint** field of [bot registration form](https://dev.botframework.com/bots/new)
 - Test the newly created bot on botframework website by clicking on the Test button
 - Click Add to skype button and start chating with the bot
 - [Learn more](https://medium.com/@AmJustSam/how-to-build-skype-bot-with-nodejs-ddec8372114c)

# Run on Heroku

 - [Procfile and worker process](http://shiffman.net/a2z/bot-heroku/) are required for Heroku deployments
 - [Deploy github code to Heroku](https://www.google.com/search?q=Deploy+Github+code+to+Heroku)
 - Update the heroku link as new message end point in bot framework website
 
# Credits

[Usama Tahir](https://github.com/AmJustSam)
