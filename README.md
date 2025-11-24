# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
 
## Aim: 
 To launch an EC2 instance in AWS cloud. 
 Procedure: 
Step 1: Sign in to AWS Management Console
Go to   https://console.aws.amazon.com

Sign in with your credentials.


 Step 2: Open the EC2 Dashboard
In the AWS Console, search for EC2 in the services search bar.
Click on EC2 to open the EC2 Dashboard.


 Step 3: Launch a New Instance
Click “Launch Instance”.

 Step 4: Configure Basic Details
Name your instance (optional but helpful).
Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux, Ubuntu, Windows).
Choose an Instance Type (e.g., t2.micro for free tier).


 Step 5: Configure Key Pair (Login)
Under Key pair, select an existing key pair or create a new one.
Download and store the .pem file safely.
You’ll use this to SSH into the instance later.


 Step 6: Configure Network Settings
Choose a VPC and subnet (default is usually fine).
Select or create a security group:
Allow SSH (port 22) for Linux or RDP (port 3389) for Windows.

Optionally open HTTP/HTTPS if you’re running a web server.


 Step 7: Configure Storage
Set the storage volume size (default is typically 8GB).
You can adjust it depending on your needs.


 Step 8: Review and Launch
Review your settings.
Click Launch Instance.


 Step 9: Connect to Your Instance
Once the instance state is running, select the instance.
Click Connect, and follow the instructions:
For Linux: Use SSH and your .pem file.
For Windows: Use RDP and the password generated with your key.

## Snapshot: 

![image](https://github.com/user-attachments/assets/2bf4ab5e-9fae-4861-b95e-cc0614dde1dd)

![image](https://github.com/user-attachments/assets/5ce844f8-392d-4327-adb3-572189d61678)

![image](https://github.com/user-attachments/assets/cd966dcd-583f-4303-bb80-aeddf90f6eb6)

![image](https://github.com/user-attachments/assets/32cd179f-3beb-4d21-8a64-8fc78eca7ecd)

## Result: 
Therefore, an EC2 instance is launched in AWS cloud






















Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
