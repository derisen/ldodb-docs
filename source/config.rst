.. _config:

Configuration
=============

Most of the application is configured with the symfony parameters.yml
file in app/config/parameters.yml.

.. code-block:: yaml

   parameters:
     # database configuration
     database_host: 127.0.0.1
     database_port: ~
     database_name: ldodb
     database_user: ldodb
     database_password: hotpockets

     # mailer configuration
     mailer_transport: smtp
     mailer_host: 127.0.0.1
     mailer_user: null
     mailer_password: null

     # A secret key that's used to generate certain security-related tokens
     secret: d2d31e391ebe8e7f307f64f1348d2c84b030cc66

     # Router and cookie information
     router.request_context.scheme: http
     router.request_context.host: 127.0.0.1
     router.request_context.base_url: /

     # words in a generated excerpt
     nines_blog.excerpt_length: 50

     # number of posts to show on the home page
     nines_blog.homepage_posts: 3

     # number of posts to show in the drop down menu.
     nines_blog.menu_posts: 5
