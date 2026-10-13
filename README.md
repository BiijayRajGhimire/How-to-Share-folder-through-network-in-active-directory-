# How-to-Share-folder-through-network-in-active-directory-
simple way use two steps.
Run command through CMD and create .bat file   Save at window/sysvol/sysvol/ scripts login.bat

Network Drives (Public, Sales, Marketing) with appropriate    permissions in User PC1 and PC2.
1. First step give static Ip address to Ad server
<img width="874" height="258" alt="image" src="https://github.com/user-attachments/assets/eed1b89c-3d2a-4e26-8cda-1c138ed4447a" />
<img width="887" height="273" alt="image" src="https://github.com/user-attachments/assets/9c1f5eb6-c1ca-41a7-af9e-1f8b076e114d" />
Add Roles and Features
1.	Click: 
2.	Manage → Add Roles and Features
3.	Click Next
4.	Select: ✅ Role-based or feature-based installation
5.	Click Next
<img width="975" height="263" alt="image" src="https://github.com/user-attachments/assets/e7bcf903-616e-4a88-b928-0c601fc6ce45" />
•	Choose your server (local server)
•	Click Next
Check: ✅ Active Directory Domain Services
A popup will appear
Click:
Add Features
Click Next → Next → Install
 Step 3: Click promoter this server to a domain controller
<img width="852" height="311" alt="image" src="https://github.com/user-attachments/assets/739a6ced-3be0-413a-8742-267f82dba1b1" />
Add a new forest and fill Root Damian name
<img width="975" height="436" alt="image" src="https://github.com/user-attachments/assets/e6995ae8-04ca-4ca8-b750-ff04f1edf91a" />
Then click in ok
Domain controller option fill Password it your choice
<img width="975" height="397" alt="image" src="https://github.com/user-attachments/assets/194774e9-2b7e-4d6a-bd50-13ec72fb0447" />
Then Next 3 time and install
After Installation server need to restart. Then you can see Everestitt.com/administrator 0 domain name
<img width="975" height="273" alt="image" src="https://github.com/user-attachments/assets/6932427b-61b0-49ec-bb04-ce38c8461078" />
Check at Roes and service group AD DS is install properly or not?
<img width="975" height="331" alt="image" src="https://github.com/user-attachments/assets/7bece1d0-3cb5-4364-ac16-d9f0ee8d2dc8" />
 Click in tools and choose Active directory users and computer
<img width="974" height="304" alt="image" src="https://github.com/user-attachments/assets/69afbc44-3fb7-4bf3-bc06-b1f5ff5884ec" />
Click in tools and choose Active directory users and computer
<img width="975" height="364" alt="image" src="https://github.com/user-attachments/assets/179029fa-d0c0-4924-b386-74e0b17ad1eb" />
<img width="290" height="82" alt="image" src="https://github.com/user-attachments/assets/e1939175-2b1b-4e9c-b28d-8ade0b92ee0f" />
Add at group
<img width="839" height="348" alt="image" src="https://github.com/user-attachments/assets/43ca32fa-82c1-4542-8497-4a21cb51d670" />
<img width="746" height="365" alt="image" src="https://github.com/user-attachments/assets/1a989b83-0ad3-4e76-a1a7-03a95ea15f0a" />
<img width="627" height="343" alt="image" src="https://github.com/user-attachments/assets/7d0818df-2cee-43cc-9188-81b0573e73a6" />
Share files with specific people and add users.
<img width="733" height="360" alt="image" src="https://github.com/user-attachments/assets/e83f4f9a-f6ef-4d15-bed8-1eb59b941edf" />
<img width="764" height="290" alt="image" src="https://github.com/user-attachments/assets/e425231e-dd60-4236-8de4-525e6a777fbc" />
<img width="789" height="119" alt="image" src="https://github.com/user-attachments/assets/7c821f64-3ce6-44d1-8e33-3291d73f65f9" />
<img width="744" height="320" alt="image" src="https://github.com/user-attachments/assets/efd2ec1d-3657-4c64-a159-966fbdeb2cf1" />
<img width="790" height="166" alt="image" src="https://github.com/user-attachments/assets/59e3fdbe-4b2f-4ff8-8f82-bc1a169c5d26" />
Public files give access to Domain users
<img width="846" height="184" alt="image" src="https://github.com/user-attachments/assets/4f561d23-2a34-4747-8dfd-3537b816e18a" />
<img width="832" height="148" alt="image" src="https://github.com/user-attachments/assets/6b825d81-d9af-4a15-84d8-5884f825938d" />
Open Notepad run as administrator
<img width="707" height="305" alt="image" src="https://github.com/user-attachments/assets/49ee4891-183b-4acf-83a2-b8a5f2c4d200" />
<img width="702" height="253" alt="image" src="https://github.com/user-attachments/assets/8de9412c-61d7-4a8a-a17f-6255bea5cf8d" />
Save at window/sysvol/sysvol/Everestitt.com/scripts login.bat
<img width="851" height="286" alt="image" src="https://github.com/user-attachments/assets/a040ee2a-9366-458d-82fc-3ad24bf4e9d1" />
Let join Pc at domain Everestitt.com Sales pc and Marketing Pc
<img width="974" height="428" alt="image" src="https://github.com/user-attachments/assets/2884971f-f844-4eb2-9750-c8081bad11e8" />
<img width="969" height="410" alt="image" src="https://github.com/user-attachments/assets/f4d32fd7-20f1-46dc-a794-0c5992a311b9" />
Connecting server, we have
<img width="884" height="353" alt="image" src="https://github.com/user-attachments/assets/e2aec933-59e0-456b-8961-1ae1c2eed09f" />
Test file run at Command prompt
<img width="693" height="263" alt="image" src="https://github.com/user-attachments/assets/0b1e34ef-730a-409f-b8f7-037c690f798d" />
<img width="975" height="373" alt="image" src="https://github.com/user-attachments/assets/037eba21-0923-4634-a935-62d4da7f3886" />
Marketing pc
<img width="975" height="334" alt="image" src="https://github.com/user-attachments/assets/b125f6cb-481f-4fbc-9994-3394da7976d2" />
can access map drivers anywhere in the department.
Right click user properties and click in profile
14. Now adding .bat file to user profile so users
<img width="839" height="311" alt="image" src="https://github.com/user-attachments/assets/2f7baa06-233a-473b-b738-feaf5b1df707" />
Paste .bat file at profile and hit apply and ok
<img width="633" height="430" alt="image" src="https://github.com/user-attachments/assets/c21c762e-2b28-48c4-99d2-9a59265ea73d" />
After this process, user can easily access drive anywhere in the marketing department login.
<img width="975" height="333" alt="image" src="https://github.com/user-attachments/assets/e675f8b3-5524-42e6-a97a-6804b4c156be" />

