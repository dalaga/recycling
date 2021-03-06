My Building Doesn't Recycle
===========================

Crowdsourcing data about which residential buildings do not have recycling in Chicago

The app can currently be found at http://mybuildingdoesntrecycle.com

Requirements
------------

* [Node.js](http://nodejs.org/)
* [MongoDB](http://docs.mongodb.org/manual/)
* [Memcached](http://memcached.org/)


Getting Started
---------------
For more detailed instructions see the [wiki](https://github.com/open-city/recycling/wiki)

* install dependencies
  `npm install`
* Run the schema migrations
  `npm migrate:all`
* Run `mongod` and `memcached` on default ports
* run the app
  `node server.js`
* Then visit [http://localhost:3000](http://localhost:3000) in your browser.

Tests
-----
Run the tests with ```npm test```

