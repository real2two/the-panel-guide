Part of settings.json:
```json
  "pterodactyllink": "Pterodactyl Panel URL",
  "pterodactylapi": "Pterodactyl Panel API Code",
```

--- ---

You change "pterodactyllink" to the Pterodactyl Panel URL. Example: `"pterodactyllink": "https://demo.pterodactyl.io/",`.

--- ---

In order to get "pterodactylapi", you must first make an application API code. 

In order to do so:

1. You must have administrator on a Pterodactyl Panel.

2. Go to "(Pterodactyl Panel URL)/admin/api".

3. Click "Create New".

![1](https://raw.githubusercontent.com/real2two/the-panel-guide/master/images/pterodactyl/pterodactyl-1.png)

4. Set up the permissions and API description then click "Create Credentials".

![2](https://raw.githubusercontent.com/real2two/the-panel-guide/master/images/pterodactyl/pterodactyl-2.png)

5. Copy the API code.

![3](https://raw.githubusercontent.com/real2two/the-panel-guide/master/images/pterodactyl/pterodactyl-3.png)

6. Paste it to `"pterodactylapi": "HERE",` in settings.json.
