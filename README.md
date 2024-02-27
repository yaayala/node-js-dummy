# node-js-dummy
This is a dummy node js application using express to setup a web app showing the version. 

To deploy run:
1. npm ci or npm install  
2. node index.js

Or you can build a contenerized version:
1. docker build -t node-dummy .
2. docker run -p <localhost-port>:8081 node-dummy