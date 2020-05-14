You can change "port" to 80 so just "IP Address" connects to the website instead of "IP Address:Port".
```
"port": 80
```
--- ---
You need to set the link of the panel. This does not give you an IP address nor domain but you need to put the current domain or ip address of the panel.
```
"link": "(Domain URL Here)",
```
The "(Domain URL Here)" can either be the domain or ip address.

After you set up the link, you need to set it up on Discord too, except instead of the link, you need to add `/callback` at the end of the link.

![5](https://raw.githubusercontent.com/real2two/the-panel-guide/master/images/discord/discord-5.png)

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
