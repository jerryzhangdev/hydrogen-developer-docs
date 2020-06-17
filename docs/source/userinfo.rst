GET: Userinfo
==============

Get the info on a user

HTTP METHOD - **GET**

Request URL - https://api.hydrogenbot.xyz/v2/userinfo/:id

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
     - ID of the user to get

**RETURNS**

*200*

.. code-block:: json

   { "id": "539195184357965833", "name": "Airbus A350-1000#9999", "level": 92, "hydrogens": 8902815, "premium": 2 }
   

*404*

.. code-block:: json

   { "error": "no user found!" }
   
*401*

.. code-block:: json

   {  "status": 401, "error": "Unauthorized", "message": "Headers value `Auth` undefined."   }
   
