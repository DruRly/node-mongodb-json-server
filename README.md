node-mongodb-json-server
========================

Testing setting up a json-server with Node, Restify and node-mongodb-native.

Restify can very easily be replaced with Express, probably just by changing the require-module to use Express.
See here the reason why you might want to use Restify: http://mcavage.github.com/node-restify/

This json-server saves notes to a database.

I also did a similar test with mysql: https://github.com/frodefi/node-mysql-json-server

I will next do a test using mongodb and socket.io, then I will also include authentication.
If you don't want to use socket.io, you can easily take out the authentication part and put it in here.
See https://github.com/frodefi/node-mongodb-socketio-server

Please feel free to use this code as you like :)
