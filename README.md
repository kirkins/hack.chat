<i>Note: Versions above 0.12.18 throw an error but still work</i>
### Hack.chat.games MOD
* adds real-time gaming in chat room
* currently only tic-tac-toe (chess soon?)
* hover on right side and click another user's name to start game

[![hack.chat screenshot](https://raw.githubusercontent.com/kirkins/hack.chat.games/master/screenshot.png)](https://youtu.be/NwusOLDp60s?t=5s)

## Local install

### Server

node v0.12 or higher is required to run the server.

* `git clone https://github.com/kirkins/hack.chat.games.git`
* `cd hack.chat`
* `npm install`
* Copy `config-sample.json` to `config.json` and edit if needed.
* `npm start` or `node server.js`

### Client
* `cd client`
* `npm install -g less jade http-server`
* `make`
* `http-server`

Change the "frontpage" text in `client.js` to your liking, and go to http://127.0.0.1:8080.
