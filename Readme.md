Start Web Page -


1- You must install connect and server-static modules:

npm install connect serve-static


2- You must create server.js file that contains:

var connect = require('connect');
var serveStatic = require('serve-static');
connect().use(serveStatic(__dirname)).listen(8000);


3- Run your command:
node server

4- for testing add a HTML file (index.html) in your nodejs directory

5- Open the browser and put :
http://localhost:8000/index.html
