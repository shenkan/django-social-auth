Tumblr
^^^^^^^^^^

Tumblr uses OAuth 1.0a for authentication.

- Register a new application at http://www.tumblr.com/oauth/apps

- Set the ``Default callback URL`` to http://[your domain]/

- fill ``OAuth Consumer Key`` and ``Secret Key`` values in your Django settings::

      TUMBLR_CONSUMER_KEY = ''
      TUMBLR_CONSUMER_SECRET = ''

.. _Tumblr API: http://www.tumblr.com/docs/en/api/v2
