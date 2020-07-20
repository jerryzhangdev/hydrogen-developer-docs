WEBSOCKET
=========

Hydrogen Websocket is used for developers to create application for realtime message use, for example global chat.

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
   
