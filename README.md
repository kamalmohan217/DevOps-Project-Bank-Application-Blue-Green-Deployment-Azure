# DevOps-Project-Bank-Application-Blue-Green-Deployment-Azure

Architecture diagram for project is shown below. 

![image](https://github.com/user-attachments/assets/34d58f91-bd2f-4b07-8b88-b28d3e8c2d43)

Architechture diagram for Blue-Green deployment is shown below.

![image](https://github.com/user-attachments/assets/7794d670-bff9-4a4a-91a0-2b10135e5e00)
![image](https://github.com/user-attachments/assets/dd814476-2663-4913-afc4-77fb6e562a72)
![image](https://github.com/user-attachments/assets/32d277c5-01d0-449c-877a-9d7a5268c38b)

The source code was present in Azure Repos as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/74e4727f-3dc2-452e-ac34-c6b40c6f6754)

Created Azure Artifacts Feed with the name of bankapp and provided contributor permission on it. Updated the pom.xml as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/01cac05f-dd39-4ff6-996a-7e328a2565d3)

Srrvice Connection has been created for SonarQube, Maven Azure Artifacts Feed and Docker Registry as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/a431f114-3be3-4648-8dab-a30982202b83)

Two Azure Pipelines has been created as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/6327f255-4bb2-4e2f-96f6-bd30d06735ae)

Access the Application after running the two Azure Pipelines as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/1f0fcbbc-3d7b-45a8-ae86-803d46ebc636)
![image](https://github.com/user-attachments/assets/d8d0ffe7-fee2-4425-8140-96d7a98e06d4)

Application Pod, Deployment and Service will be created as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/187b81ba-1320-4544-998a-9ca34307962e)

As per the requirement the login page (login.html) of the Bank Application has been changed and its name is changed from Goldencat to GoldenHawk and bankapp Azure Pipeline has been run. 
We can get the rollout and list the multiple versions of it as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/4276336d-ec77-4ca8-9e6a-902690b41ca7)

For checking purpose I have changed the service type of bankapp from ClusterIP to LoadBalancer as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/8fb3b635-62dd-4466-afcf-2578dd389346)
![image](https://github.com/user-attachments/assets/f948c4fc-1b56-4164-b8a1-e360e01b5275)
