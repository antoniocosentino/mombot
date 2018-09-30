
# Mombot

Mombot is a bot for Slack.

## What does he do?
You can direct message him and he will reply "your mom". It works also when mentioned inside a public or private channel (if he's invited in the channel obviously).

![screenshot](screenshot.png)

## Is this all he does?!?
Yep.

#
## Setup
### Natively (Node.js)
Clone this repo, then run:

`npm install`

You also need to create two environmental variables:

`export BOTPORT=80` the port where you want to run the bot

`export TOKEN=xxx-xxx` this is the token you get from Slack

When this is done you can simply run it with:
`npm start`

#
### Docker
First create a file on root level called `variables.env`

Then put here the environmental variables, as explained previously.

Example:
```
TOKEN=xxx-xxx
BOTPORT=80
```

When this is done you can run it with Docker:

`docker-compose up --build`

#

That's it. Enjoy!
