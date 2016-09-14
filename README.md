Dinkly Restful API Plugin v1.00
===============================

A ready-to-go Restful API for your Dinkly project, useful for interaction with JS MVC frameworks.


Installation
------------

  1. Move the `restful_api` folder into your dinkly project's `plugins` folder

  2. Add the following lines under the `plugins` section of your `config/config.yml` file:

    ```yaml
    restful_api:
            apps:
                api:
                    app_name: Dinkly API
                    base_href: /api
                    enabled: true
                    default_module: router
    ```

Usage
-----

Just hit the following URL: `/api/router`


License
-------

The Dinkly Uptime Responder plugin is open-sourced software licensed under the MIT License.


Contact
-------

  - lewsid@lewsid.com
  - github.com/lewsid
