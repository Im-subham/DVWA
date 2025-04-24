Security level is currently: low.

we have name and message field let's put our payload in message:

we have to just increase the length of input box of name by simply editing the value form html.
payload=<script>alert(1)</script>

Security level is currently: medium.

we have name and message field let's put our payload in message:

we have to just increase the length of input box of name by simply editing the value form html.
![Screenshot 2025-04-25 030842](https://github.com/user-attachments/assets/7a6b0608-d170-4dca-a53a-9ec3725b239f)

payload=<scr<script>ipt>alert(1)</script>

![Screenshot 2025-04-25 030805](https://github.com/user-attachments/assets/a0e82480-ee5a-42b2-98e6-fd6e8b9897d2)


Patch:

Escape output when displaying user-submitted content using htmlspecialchars().

Validate and sanitize input before storing, but always escape on output (because raw data might be needed elsewhere).
