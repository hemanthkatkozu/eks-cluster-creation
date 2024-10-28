# eks-cluster-creation

step 1:

![image](https://github.com/user-attachments/assets/98002a66-b47b-4cdb-b5ca-37cdf5c73c37)


step2:
by default we dont have cluster IAM role, we need to create it 

<img width="912" alt="image" src="https://github.com/user-attachments/assets/683895a6-2497-4fb4-9d33-9f65d2233a62">

![image](https://github.com/user-attachments/assets/1017f272-a8fc-49b6-831f-2959cbb07210)

![image](https://github.com/user-attachments/assets/17a3d1ac-1b89-4b68-b57f-a5303aa844a9)

ste3: click on next > next

enter the role name & tags as per standards & click on create role
![image](https://github.com/user-attachments/assets/d706d771-920c-4c6d-80fa-cc2914fcc545)

![image](https://github.com/user-attachments/assets/d295d09c-148c-4b8d-afe7-a6847ec675d3)

step 4: attach additional policies required for the role
![image](https://github.com/user-attachments/assets/594a3725-a722-49e1-adbb-adb26ae4b839)

![image](https://github.com/user-attachments/assets/b71abbee-f46d-40f4-8316-e4205263a092)

step5: select the role created

![image](https://github.com/user-attachments/assets/a8dd0b32-8c0a-4559-9199-d59b6542f4bc)

![image](https://github.com/user-attachments/assets/8b275a51-762d-4f06-a42c-9b3b3c1581b5)

![image](https://github.com/user-attachments/assets/7165b8b9-daab-482e-92b0-445c243cf162)


Add tags as per requirement and select next

![image](https://github.com/user-attachments/assets/6d677165-d244-4c7b-bb77-991c0ea59643)

select the default security group & security group should contain following rules --> ssh 22, http 80, https 443
![image](https://github.com/user-attachments/assets/8cd32f3b-df13-4c6b-ac32-f5769d630f2d)

![image](https://github.com/user-attachments/assets/337b86a5-ff0d-40a8-a88c-49e9b349a9ea)

![image](https://github.com/user-attachments/assets/514032c0-9173-4638-a5a5-bf863d7ec07c)

![image](https://github.com/user-attachments/assets/2d90c3cc-eb6b-453b-9f48-6e3563fb7e07)

![image](https://github.com/user-attachments/assets/498e07bc-15b1-4106-86e7-318a94e640d4)

Remove all addons

![image](https://github.com/user-attachments/assets/97c6d245-a96a-4afc-ad76-9ab99f6ba6bb)


select create cluster









