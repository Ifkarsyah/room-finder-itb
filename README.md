# ITB Room Finder

Line bot that takes input ITB room code from user and then replies with the building's name that room placed.

### Prerequisites

1. Git
2. [Python 2 or 3](https://www.python.org/)
3. [Line Developer Account](https://developers.line.me/en/)
4. Line Messaging API app
5. [Heroku Account](https://heroku.com)


### Installing
Clone this repository.
```
git clone https://github.com/Ifkarsyah/room-finder-itb.git
```
Get your "Channel-Access-Token" and "Channel-Secret" and place them in row 16-17

```
line_bot_api = LineBotApi('Channel-Access-Token')
handler = WebhookHandler('Channel-Secret')
```

Go to your Heroku account and go to "Deploy" tab and follow their [instruction](https://dashboard.heroku.com/apps/{YOUR-APP-NAME}/deploy/heroku-git).

## Example Use

Add the bot [here](https://line.me/R/ti/p/@rok8141p).


## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details
