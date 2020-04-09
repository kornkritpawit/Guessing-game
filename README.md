# Guessing-game

Created by Kritpawit Soongswang 6110545414

## Prerequistic
1. Node
2. Mongodb or run Mongodb in Docker
## Installation
1. Start your mongodb server
2. Install package (cd to your server.js directory)
```
$ npm install
```
3. Configure your database location and the collection in server.js

```javascript
const url = 'mongodb://localhost:27018/GuessingGame';
const dbName = 'GuessingGame';
```
4. run the script (same directory as server.js)

```terminal
$npm start
```
6. The server will use port 3000.
```
localhost:3000
```
8. Enjoy the game.