Security level is currently: low.

In url there is GET parameter page used for including file.

url:http://192.168.57.222/vulnerabilities/fi/?page=include.php

By changing this file location we can read file on server.

url:http://192.168.57.222/vulnerabilities/fi/?page=/etc/passwd

![Screenshot 2025-04-25 031445](https://github.com/user-attachments/assets/fb6f8581-0e5f-46c0-8411-0fc4e62269cb)


Patch:

Don’t use user input in include/require.

Whitelist files or use fixed file mappings.
