# mongochat   
A simple chat app built using sockets , express , mongoDB that can be used between multiple devices connected to same remote server.

 
*  Clone the repo
*  Download and Install nodeJS
*  npm install
*  start mongod
*  npm start
*  On local machine: localhost:3000

### To enable multi device chat

In index.html, type your public IP address in place of public_ip
```
var socket = io.connect('public_ip:4000');
```

<b>use the same address ('public_ip:4000') on any remote device connected to the same Internet gateway.</b>

