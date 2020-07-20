WEBSOCKET: globalsend
================

Send a message to hydrogen global chat.

Request URL - wss://websocket.hydrogenbot.xyz

Send Data - { t: "globalsend", b: { Authorization: "Your api token", content: "content to send" } }
**RETURNS**

*200*

.. code-block:: json

   {
    error: false,
    s: 200,
    b: {
      handshakesuccessful: true,
      embedinfo: {
        title: 'Hydrogen Global Chat',
        type: 'rich',
        timestamp: '2020-07-20T16:38:56.682Z',
        color: 4189259,
        fields: [Array],
        thumbnail: [Object],
        image: null,
        author: [Object],
        footer: [Object]
      }
    },
    e: null
  }
   
