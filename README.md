Forked Copy
=============================

The original repository this is from is essentially frozen. It includes reference material for an article on game networking, so the author is understandably reluctant to change it. 

Here's what my changes do:
* switches `game.core.js` from object oriented to a data oriented approach
* uses es modules everywhere
* moves number functions to not extend the built in number type


Realtime Multiplayer In HTML5
=============================

Read the article here : 
http://buildnewgames.com/real-time-multiplayer/

View the demo here :
http://notes.underscorediscovery.com:4004/?debug

An example using node.js, socket.io and HTML5 Canvas to explain and demonstrate realtime multiplayer games in the browser.

## Getting started (Using npm package.json)
* Get node.js
* run `npm install` inside the cloned folder
* run `node -r esm app.js` inside the cloned folder
* Visit http://127.0.0.1:4004/?debug

## Getting started (Manual install)

* Get node.js
* Install socket.io `npm install socket.io`
* Install node-udid `npm install node-uuid`
* Install express `npm install express`
* Install esm for modern module support `npm install esm`
* Run `node -r esm app.js` inside the cloned folder
* Visit http://127.0.0.1:4004/?debug

## License

MIT Licensed. 
See LICENSE if required.

