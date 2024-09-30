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
![image](https://github.com/user-attachments/assets/f948c4fc-1b56-4164-b8a1-e360e01b5275)
![image](https://github.com/user-attachments/assets/c6ca5337-430f-4355-9105-b08085f85ed7)

After checking when you get assured Application is working fine, changed the service type from LoadBalancer to ClusterIP as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/05557e76-3f68-484c-8381-18ecfc08e6be)

Finally promote the rollout as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/69e4c9ee-86bc-4159-807d-ca41d2c90145)

List the Rollout for stable and preview status as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/d4f1695e-9e36-412a-af98-04d0e70ce105)

Finally access the application as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/f8e6cca0-6263-494b-bacd-c7daabedb9b3)
![image](https://github.com/user-attachments/assets/7436cd58-a6f7-4f06-bc68-02de88236050)

After running the Azure pipelines the screenshot for SonarQube and Azure Artifacts are as shown in the screenshot attached below.
![image](https://github.com/user-attachments/assets/47793a9a-f571-4ea4-8a90-21337c1a9c00)
![image](https://github.com/user-attachments/assets/9b3f8b31-820d-4465-a715-6170944cce4f)

<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
```
Source Code:- https://github.com/kamalmohan217/Bank-App.git

Helm Chart:-  https://github.com/kamalmohan217/helm-repo-for-Blue-Green-Deployment.git
```
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
```
Reference:-  https://github.com/Goldencat98/Bank-App.git
```
