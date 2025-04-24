Security level is currently: low.

we have name field which is reflecting on page.

payload = <script>alert(1)</script>

It triggers an alert pop up with cookie value.

![Screenshot 2025-04-25 013527](https://github.com/user-attachments/assets/be51887b-d633-477e-9418-72a2d3ad989f)
![Screenshot 2025-04-25 013504](https://github.com/user-attachments/assets/5c67186e-7063-430d-bb7f-a35c84d34232)

Security level is currently: medium.

we have name field which is reflecting on page.

payload = <scr<script>ipt>alert(1)</script>

And this is the result
![Screenshot 2025-04-25 030125](https://github.com/user-attachments/assets/92186498-5e1d-4b6a-b022-2d5e81b275cf)


Patch:

Escape output using htmlspecialchars() in PHP.

Use a content security policy (CSP) header.
