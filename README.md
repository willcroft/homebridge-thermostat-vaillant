# homebridge-thermostat-vaillant

A Vaillant vSMART thermostat plugin for [Homebridge](https://homebridge.io).

To use this plugin, you need to register an application on the Netatmo developer platform:

1. Visit https://dev.netatmo.com/apps/createanapp
2. Register for an account and log in
3. Create a new application, completing the `name`, `description` and contact `name` and `email` fields
4. Save and copy the resulting `client_id` and `client_secret` fields into the configuration in Homebridge

# Configuration

```
"accessories": [
    {
        "accessory": "Vaillant Thermostat",
        "name": "Vaillant vSMART",
        "client_id": "<client_id>",
        "client_secret": "<client_secret>",
        "username": "",
        "password": ""
    }
],
```
