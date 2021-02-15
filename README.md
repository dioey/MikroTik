# MikroTik
Script MikroTik too Block spam
This Script Download blacklist ip from various source to MikroTik, add raw firewall to "blacklist" address list 

The new parameter "output=user" provided new scripting capabilities that I decided to take full advantage of.
- the script does not need third-party servers, since address lists are downloaded directly from the source and processed directly on the router.
- the script does NOT save the downloaded files to the disk (thereby preventing premature wear and failure of the disk).
- the script can be adapted to download and process any number of address lists of a similar format (the maximum file size is 63 KiB (64512 bytes). It is better than 4 KiB).

all Credit to Shumkov in forum.mikrotik.com
