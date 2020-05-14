If it is your first time running the panel, you may want to update database.json in order to add your account manually into the database because it will say "An error has occured while creating your account." It says this because the email on the Discord account already exists on the Pterodactyl Panel.

Turn off the process first.

You should manually set database.json like this:
```json
{
  "userid_DISCORDUSERID": "PTERODACTYL USER ID",
  "user_DISCORDUSERID": "EMAIL",
  "maxram_DISCORDUSERID": 1024,
  "maxdisk_DISCORDUSERID": 1024,
  "maxcores_DISCORDUSERID": 1,
  "maxservers_DISCORDUSERID": 1,
  "password_DISCORDUSERID": "(unknown)"
}
```

Replace `DISCORDUSERID` with your Discord user ID.

Replace `PTERODACTYL USER ID` with your Pterodactyl user ID.

Replace `EMAIL` with your email.

After that, save it. 

Then, turn on the panel again.
