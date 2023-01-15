# AWS-Database
Hands-on Lab on AWS Database Configuration

## LAB Prerequisites
  1. Familiarity with basic AWS Cloud Computing concepts and terminology
  2. An AWS account with an active subscription
  
## Lab Diagram

<img width="857" alt="Screenshot 2022-12-14 at 11 38 19 AM" src="https://user-images.githubusercontent.com/101164153/207667626-1ba76906-b05e-42e3-977e-49617c92220e.png">

## Implementation Steps
  1. Enable the Multi-AZ Feature in RDS.
  2. Enable the Backup in RDS.
  3. Create a Read Replica.
  
### Step 1: Enable the Multi-AZ Feature in RDS.
  1. Log in to the AWS Management Console.<img width="1535" alt="Screenshot 2022-12-14 at 11 45 49 AM" src="https://user-images.githubusercontent.com/101164153/207669023-61257aa9-e567-440d-a5df-9ea56de87e29.png">
  2. Go to Services, select Databases, and click on RDS.<img width="1728" alt="Screenshot 2022-12-14 at 11 48 59 AM" src="https://user-images.githubusercontent.com/101164153/207669888-fb27e458-944c-4cfd-a85b-c638ab6c0008.png">
<img width="1728" alt="Screenshot 2022-12-14 at 11 49 18 AM" src="https://user-images.githubusercontent.com/101164153/207669952-7c643a64-3b39-4c0a-9d91-a01460fddeb7.png">
  3. Click on Create database and then choose Standard create and select MySQL in Engine Options.
<img width="931" alt="Screenshot 2022-12-14 at 11 50 01 AM" src="https://user-images.githubusercontent.com/101164153/207669990-39351501-5b45-4e26-8154-2e835ef2611c.png">
<img width="845" alt="Screenshot 2022-12-14 at 11 55 47 AM" src="https://user-images.githubusercontent.com/101164153/207670927-3b5fb310-e435-4f5c-a0f8-7798c4136c7d.png">
