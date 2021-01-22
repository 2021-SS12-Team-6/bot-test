# bot-test
Practice making a discord bot (using JS)

### Basic setup

1. Clone your repo (so url is automatically in package.json)

2. Check if you have npm installed
```
$ npm -v
```
__If you're not starting new, and just want to copy this repo, ignore steps 3-6 and just do:__
```
$ npm install 
```  
In order to install dependencies listed in package.json. 

3. Initialize project (in project directory)
```
$ npm init
```
(Optional: configure npm test)

(dependencies listed in package.json)

4. Install discord.js 
```
$ npm install discord.js
```
(Optional: npm install eslint)

5. Create new application in Discord dev portal [here](https://discord.com/developers/applications) & add bot

6. Hide API tokens within .env file. Use dotenv package to manage keys.
```
 npm install dotenv
```

> The .env file should be created in the main directory contain the following lines:  
> TOKEN = YOUR_DISCORD_API_TOKEN_HERE

### Deploy
(TODO)




