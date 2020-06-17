Migrate to Hydrogen API version 2
=================================

prerequisites
-------------

1. You need to have hydrogen in your server.

2. You need to make sure hydrogen can dm you.

3. You have access to your original api codes


Steps
-----

1. In **EACH** hydrogen api request, change the v1 in the url to v2.

2. Send an request to `authorize <https://developer.hydrogenbot.xyz/en/latest/authorize.html>`_ and reply to hydrogen's message with the code it supplies you.

3. Apply the Auth token hydrogen sent to you on discord to each Auth header after successful authorization.

4. Try it out. If not working, check if your url have v1 inside of the version input, check did you do step 2 correctly, check if headers is inputed wrongly. If still not working, contact us `here <https://discord.gg/SNNS24r>`_

5. If you are doing this before June 20th, 2020, repeat step 1 - step 4 after june 6th as database will be reset after june 20th.
