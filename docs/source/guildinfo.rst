GET: Guildinfo
==============

HTTP METHOD - **GET**
Request URL - https://api.hydrogenbot.xyz/v2/guildinfo/:id

.. list-table:: **Headers**
   :widths: 25 25 50
   :header-rows: 1

   * - Name
     - Type
     - Description
   * - Auth
     - string
     - Authorization Token obtained from `Authorize <https://developer.hydrogenbot.xyz/en/latest/authorize.html>`_ endpoint
     
.. list-table:: **Query Parameter**
   :widths: 25 25 50
   :header-rows: 1

   * - Name
     - Type
     - Description
   * - id
     - string
     - ID of the guild to get

**RETURNS**

*200*

.. code-block:: json

   { "id": "713166270052171910", "name": "𝙃𝙮𝙙𝙧𝙤𝙜𝙚𝙣 𝙎𝙩𝙪𝙙𝙞𝙤",  "globalchatenabled": true, "prefix": "H!",   "Infinite": true }
   

*404*

.. code-block:: json

   { "error": "Could not find guild" }
   
*401*

.. code-block:: json

   {  "status": 401, "error": "Unauthorized", "message": "Headers value `Auth` undefined."   }
   
