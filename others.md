You can change "port" to 80 so just "IP Address" connects to the website instead of "IP Address:Port".
```
"port": 80
```
--- ---
You need to setup a callback link.
```
"callbacklink": "(Domain URL Here)/callback",
```
The "(Domain URL Here)" can either be the domain or ip address.

After you set up the callback link, you need to set it up on Discord too.

--- ---
You can skip the install scripts using:
```
"skipinstallscripts": 1,
```
You can also enable install scripts using:
```
"skipinstallscripts": 0,
```
After you set it as that and then turn on the process, you need to turn off the process and turn it on again for it to do the full effect.
--- ---
You can disable new users from registering using:
```
"nonewusers": true
```
You can enable new users from joining again using:
```
"nonewusers": true
```
--- ---
You can enable a whitelist of people who can login using:
```
"whitelist": ["discord user id", "another user id"],
```
You can disable whitelist using:
```
"whitelist": null,
```
