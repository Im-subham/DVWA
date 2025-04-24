The goal is to brute force an HTTP login page.

Security level is currently: High.
On submitting the username and password we see that it is using get request

![6075474992927196946](https://github.com/user-attachments/assets/624b3778-91c9-448e-9f45-8b7802a75803)

![6075474992927196947](https://github.com/user-attachments/assets/f6f30f3d-85c8-40e6-ad51-29904f0c4c09)

So let’s use burp suite for brute force:
First i capture the request and then send that request to the intuder and their i set payload at username and password section
At the both section i uses my own username and password txt file 
![6075474992927196948](https://github.com/user-attachments/assets/8c675166-9071-44d1-8c7c-fa9a2360aefa)

After setting all the things i started the brute forcing....
![6075474992927196949](https://github.com/user-attachments/assets/d28141be-5e30-4f27-a3d7-c1abad960adf)

After the completion of brute forcing i the uniqe length in result
![6075474992927196950](https://github.com/user-attachments/assets/9604b1fb-43f2-490a-996d-da1a9f0c6a94)

 And from that uniqe result i get the correct username and password.
 
PATCHES
Implement rate limiting (e.g., block IP after 5 failed attempts).

Add CAPTCHA after a few failed attempts.

Log all login attempts and alert on multiple failures.
