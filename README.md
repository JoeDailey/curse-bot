# curse-bot
a bot to keep track of used curses and different levels of distastefulness milestones for discord servers

### Installation instructions
- **npm install:** run this command to install the libraries
- **create auth.json file:** create an auth.json file to hold the token information for the bot
- **create curses.json file:** create a curses.json file to hold the different curses as well as user and server milestone messages
- **node bot.js:** run this command to start up the bot

### File and Directory Information
- **DB/:** holds files related to the mongodb database that keeps track of server and user counts for cuss words
- **bot.js:** houses the main code for the bot that parses messages and sends messages to servers and users when milestones are hit
- **package.json:** holds project-wide information