# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  

<img width="1350" height="592" alt="image" src="https://github.com/user-attachments/assets/9f1bf871-59cb-4de1-ac4a-73d58d850e19" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="1338" height="596" alt="image" src="https://github.com/user-attachments/assets/1ad45e18-13cf-46ef-8d8a-f205036ab135" />


<img width="1336" height="592" alt="image" src="https://github.com/user-attachments/assets/1cb60b5a-f6dc-4a4d-8b84-dea029abd825" />


<img width="1334" height="596" alt="image" src="https://github.com/user-attachments/assets/7dfdc707-e4ff-48a3-b638-3b551c4f8547" />



### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  

<img width="1344" height="590" alt="image" src="https://github.com/user-attachments/assets/afc80bff-58fa-43c1-afeb-5c161d9bb8be" />



<img width="1341" height="599" alt="image" src="https://github.com/user-attachments/assets/74c1cbe1-1176-4045-ad1e-b01e0542ead4" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Mirushika .T (212224040191)
**Course:** Introduction to Cloud Computing  

