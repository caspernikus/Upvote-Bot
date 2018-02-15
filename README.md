# Steemit Upvote Bot
Steemit Upvote Bot was created for a tutorial series on utopian.io - it's current development state is more template than a fully functioning upvote bot.
The goal is and will be to develop further functions to it, to make it a valid steemit bid based upvote bot.

## Installation
```
$ git clone https://github.com/caspernikus/upvote-bot.git
$ npm install
```

## Configuration
First rename config_default.json to config.json:
```
$ mv config_default.json config.json
```

Then set the following options in config.json:
```
{
    "account_name": "",
    "steem_node": "https://rpc.buildteam.io",
    "private_posting_key": "",
    "private_active_key": "",
}
```

## Run
```
$ node index.js
```

## Roadmap
- V.0.1:
  - Basic Upvote Template
- V.1.0:
  - Bid-Based Upvoting
