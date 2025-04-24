![Screenshot 2025-04-25 024825](https://github.com/user-attachments/assets/f6c24558-816b-417b-b1fb-aba9cac4f18e)

we are given with functionality to ping device. we give ip or domain to ping:

input: 127.0.0.1 
![Screenshot 2025-04-25 025159](https://github.com/user-attachments/assets/79d109d9-54e2-4c05-9198-ac1222423099)

This is about command injection so backend must be appending our input ping command.

we can give our arbitrary command to execute with the help of pipe | ,so let's create a simple payload :
 | ls

 ![Screenshot 2025-04-25 025308](https://github.com/user-attachments/assets/30e5c8bd-d30e-4e3d-abd4-8a08710f5292)
