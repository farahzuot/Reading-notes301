# Heroku with Node.js
## this note will contains how the web server work within an errors ! 

### node.js 
#### "Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications." , so node.js from the extention it is built using javascript and this is about building a servers.

1. create js file 
2. write this code :
    
    var http = require("http");

    http.createServer(function(request, response) {
      response.writeHead(200, {"Content-Type": "text/plain"});
      response.write("It's alive!");
      response.end();
    }).listen(3000); </br>

3. run this command on your terminal :
    
    node server.js

4. check it in the browser!

* Also you could check it from another device to be sure that it is a server by writing the up of your device by typing http://192.168.1.101:3000/ in your browser.


#### so till now your server is working locally , and to make it worlwide it should be with WWW "World Wide Web" . Heroku cloud application platform solve this issue. also you need the npm o be installed.

#### after writing the js code , create the content of your website .. and rund this command

    node server.js
    
    // Open your terminal within your project folder.

    git init
    git add .
    git commit -m "comment"
    heroku create
    git push heroku master
    heroku ps:scale web=1
    heroku apps:rename server
    heroku open

#### and that's it! 




