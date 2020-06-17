POST: Prefix
==============

HTTP METHOD - **POST**
Request URL - https://api.hydrogenbot.xyz/v2/prefix

.. list-table:: **Headers**
   :widths: 25 25 50
   :header-rows: 1

   * - Name
     - Type
     - Description
   * - Auth
     - string
     - Authorization Token obtained from `Authorize <https://developer.hydrogenbot.xyz/en/latest/authorize.html>`_ endpoint
     
.. list-table:: **Form Data Parameter**
   :widths: 25 25 50
   :header-rows: 1

   * - Name
     - Type
     - Description
   * - guildid
     - string
     - the id of the guild to change prefix
   * - prefix
     - string
     - The new prefix that will be changed to

**RETURNS**

*200*

.. code-block:: json

   { "status": 200, "message": "Prefix Changed", "guildid": "713166270052171910", "newprefix": "H!" }
   

*404*

.. code-block:: json

   { "status": 404, "message": "Cannot find guild with the id you provided." }
   
*401*

.. code-block:: json

   {  "status": 401, "error": "Unauthorized", "message": "Headers value `Auth` undefined."   }
   
