WEBSOCKET
=========

Hydrogen Websocket is used for developers to create application for realtime Hydrogen Data. The following data type will be sent when you create an connection to our websocket

globalchat - Emitted when someone sent something in global chat

commandcreate - Emitted when a command is triggered

**Request URL**

wss://websocket.hydrogenbot.xyz

**REQUEST EXAMPLE(node.js ws)**

.. code-block:: js

   const WebSocket = require('ws');
 
   const ws = new WebSocket('wss://websocket.hydrogenbot.xyz');
   ws.on('open', function open() {
      ws.send(JSON.stringify({ t: "globalsend", b: { Authorization: "access_token", content: "hi" } }));
   });
 
  ws.on('message', function(data){
    console.log(JSON.parse(data))
  })
   
