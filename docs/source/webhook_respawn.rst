WEBSOCKET: respawn
==================

Each request respawns the websocket connection for a ping pong connection. It basically wakes the websocket connection up.

Request URL - wss://websocket.hydrogenbot.xyz

Send Data - { t: "respawn" }

**RETURNS**

*200*

.. code-block:: json

   {
    error: false,
    t: 'respawn',
    s: 200,
    b: { respawnsuccessful: true },
    e: null
  }
   
