WEBSOCKET: respawn
==================

Required if the application need to be online for forever

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
   
