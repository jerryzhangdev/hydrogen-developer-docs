WEBSOCKET: hello
================

Recommended but not required for websocket access.

Request URL - wss://websocket.hydrogenbot.xyz

Send Data - { t: "hello" }

**RETURNS**

*200*

.. code-block:: json

   {
      error: false,
      s: 200,
      b: {
        handshakesuccessful: true,
        websocketgateway: {
          connecting: false,
          _hadError: false,
          _parent: null,
          _host: null,
          _readableState: [Object],
          readable: true,
          _events: [Object],
          _eventsCount: 5,
          _writableState: [Object],
          writable: true,
          allowHalfOpen: true,
          _sockname: null,
          _pendingData: null,
          _pendingEncoding: '',
          server: [Object],
          _server: [Object],
          timeout: 0,
          parser: null,
          _paused: false
       },
       registered: true
     },
     e: null
   }
   
