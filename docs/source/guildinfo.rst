GET: Guildinfo
==============

HTTP METHOD - **GET**
Request URL - https://api.hydrogenbot.xyz/v2/botinfo

.. list-table:: **Headers**
   :widths: 25 25 50
   :header-rows: 1

   * - Name
     - Type
     - Description
   * - Auth
     - string
     - Authorization Token obtained from `Authorize <https://developer.hydrogenbot.xyz/en/latest/authorize.html>`_ endpoint

**RETURNS**

*200*

.. code-block:: json

   {"usercount":3198,"servercount":16,"ready":1592411883650,"uptime":350138,"ping":67,"owner":"Airbus A350-1000#9999"}
   
