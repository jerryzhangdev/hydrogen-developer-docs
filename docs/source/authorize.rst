GET: Authorize
==============

HTTP METHOD - **GET**
Request URL - /v2/authorize/:userid

.. list-table:: **Query Params**
   :widths: 25 25 50
   :header-rows: 1

   * - Name
     - Type
     - Description
   * - userid
     - string
     - The userid that will be granted the api token. Verification will be sent to user with this id.
     
**RETURNS**

*200*

.. code-block:: text

   Hydrogen has sent you a message. Please respond to the message with '0QObCUnnl70B00lDhA2ZUgrA'
   
*404*

.. code-block:: json

   { "status": 404, "message": "cannot find user with id: 53919518435796583! Make sure that you could be dmed by hydrogen and you have shared at least one server with hydrogen." }
