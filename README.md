# slack-msg-reviewer

[ Node.js, Electron.js, Slack, AWS Polly ] :shipit:

> Desktop App was design to review messages of specific user in slack worck-space.

## Build Setup

``` bash
# install dependencies
npm install

# run app
npm start

# run tests
npm test

# deploy
npm package-mac

npm package-win

npm package-linux
```

### Configure

Create your own `config.js` file from `comfig-sample.js`


### Set-Up Slack Bot

* First we need to create slack-bot for particular slack-work-space

* Select _Permission OAuth Scopes_ for your slack-bot :
* * channels:history
* * groups:history 
* * im:history 
* * mpim:history 
* * channels:read 
* * groups:read 
* * im:read 
* * mpim:read 
* * users:read


### Set-Up AWS Polly
* create AWS IAM User Account with **AmazonPollyFullAccess** Access Credentials

* Also we need to choose the _voice ID_ form the list https://docs.aws.amazon.com/polly/latest/dg/voicelist.html ===> `config.js`
