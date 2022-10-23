<h1 align="center">
  <b>Save content Bot</b>
</h1> 

Contact: [Telegram](https://t.me/Killerbee87)

A stable telegram bot to get restricted messages with custom thumbnail support , made by Mahesh Chauhan. 

- works for both public and private channels
- Custom thumbnail support for Pvt medias
- supports text and webpage media messages
- Faster speed
- Forcesubscribe available 
- `/batch` - (For owner only) Use this command to save upto 100 files from a pvt or public restricted channel at once.
- Time delay is added to avoid FloodWait and keep user account safe. 

# Variables

- `API_ID`
- `API_HASH`
- `SESSION`
- `BOT_TOKEN` 
- `AUTH` - Owner user id
- `FORCESUB` - Public channel username without '@'. Don't forget to add bot in channel as administrator. 

# Get API & PYROGRAM string session from:
 
API: [API scrapper Bot](https://t.me/USETGSBOT) or [Telegram.org](https://my.telegram.org/auth)

PYROGRAM SESSION: [SessionGen Bot](https://t.me/SessionStringGeneratorZBot) or [![Run on Repl.it](https://replit.com/badge/github/vasusen-code/saverestrictedcontentbot)](https://replit.com/@SpEcHiDe/GenerateStringSession)

BOT TOKEN: @Botfather on telegram

# Deploy

Deploy your bot on `Render`

Tutorial - [Click here](https://telegra.ph/SRCB-on-Render-05-17)

Deploy your bot on `heroku`

» Method - 1:
- Star the repo, and fork it in desktop mode
- Go to settings of your forked repo
- Rename your repo by any other name
- Click on 
- <a href="https://heroku.com/deploy?template=https://github.com/newkanekibot/savebots"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="210" height="34.45"/></a></p>
 
» Method - 2:
- Star the repo, and fork it in desktop mode
- create app in heroku
- go to settings of app›› config vars›› add all variables
- add buildpacks
- connect to github and deploy
- turn on dynos
  
Buildpacks for manual deploy:

- `heroku/python`
- `https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git`

Deploy your bot on `Okteto` [Useless]
  
Tutorial for okteto - [click here](https://telegra.ph/Okteto-Deploy-04-01)

[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com)
