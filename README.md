
  ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/7513c936-065a-4489-bdbf-f27c52c99c7e)

-----------

Amazon Web Services
-----------
Amazon Web Services (AWS) is a comprehensive cloud computing platform provided by Amazon.com. It offers a wide range of services, including computing power, storage solutions, networking, databases, machine learning, artificial intelligence, analytics, security, and much more. AWS allows businesses and individuals to access computing resources on-demand over the internet, without needing to invest in and maintain their own physical infrastructure. It's a highly scalable and flexible platform, making it suitable for startups, enterprises, government organizations, and individual developers alike. In this guide I'll indicate how to create an AWS account and a virtual machine.

Requirements
-----------

- Computer with Internet Connection
- Credit Card (Required for 12 months free trial)


These are the steps to create a AWS account.
-----------

1. Access the AWS Website: Open your web browser and go to https://aws.amazon.com/.


2. Initiate Account Creation: On the AWS homepage, locate and click on the "Create an AWS Account" button in the upper right corner.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/05fa5ce3-be52-41a3-a32a-d8dbf7a8b2b8)

3. Provide Email and Password: Enter your email address and create a secure password for your AWS account. Click on verify email address.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/149d0697-c1c5-45c4-88a1-ba9d4769f1d6)
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/6dfea7df-7c5a-4bc3-82f1-891cf99f309f)
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/967b72a1-aeea-4a3c-8926-272d7c0e0e77)


4. Enter Contact Information: Fill in your full name, company name (if applicable), and phone number in the provided fields. Click on "Continue".
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/940b9c25-904e-4303-9e4b-1ab514ef843b)



5. Payment Information: Input your payment details, including credit/debit card information or bank account details. This is necessary for identity verification and to enable services beyond the AWS Free Tier limits. Click on "Verify and Add".
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/8a6f6254-6501-4ae6-8f9d-8d68cb42c26b)


6. Verify Phone Number: AWS may need to verify your phone number for security purposes. Choose whether to receive the verification code via text message or phone call, enter the code you receive, and click on "Verify code and continue".
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/51c4c195-b328-4068-ab5f-5956c1b4a47c)


8. Select Support Plan: Choose a support plan that suits your needs. You can select from Basic (free), Developer, Business, or Enterprise support plans. Once your plan is selected click complete sign up.

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/49ecdf9c-00d4-4782-b069-c6e7f2b9d9b2)

9.Select go to AWS management console and it should take you to the homepage where you can sign in with your credentials.When you're done signing in you should be able to see you console home.

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/2e45b940-d297-438f-81cb-990531ad24e1)

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/5d0ff257-10bf-47cc-ab40-7c3b175b4062)

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/3d2fbb80-40f4-42f0-8c52-ebc715c3b084)

   







-----------

These are the steps to create a virtual Machine
-----------
Sign in to the AWS Management Console: Go to the AWS Management Console and sign in to your AWS account.

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/15af8b08-7531-413b-8b33-66f128eb89ca)



Navigate to EC2 Dashboard: Once logged in, navigate to the EC2 dashboard. You can find it under the "Compute" section or by searching for "EC2" in the AWS Management Console.

Launch Instance: Click on the "Launch Instance" button to start the instance creation process.

Choose an Amazon Machine Image (AMI): Select an AMI from the provided list. An AMI is a pre-configured template that contains the operating system and other software required for your virtual machine. You can choose from various Linux distributions, Windows Server, and other operating systems.

Choose an Instance Type: Select the instance type that suits your requirements. Instance types vary in terms of CPU, memory, storage, and networking capacity. You can choose a general-purpose instance, compute-optimized instance, memory-optimized instance, etc.

Configure Instance Details: Configure additional settings such as the number of instances to launch, network settings (VPC, subnet, security groups), IAM role, monitoring options, and more.

Add Storage: Specify the storage requirements for your instance. You can add additional volumes if needed and choose the type of storage (e.g., SSD, HDD) and its size.
Configure Security Group: Define security group rules to control the traffic to your instance. You can specify inbound and outbound rules to allow traffic based on protocols, ports, and IP addresses.

Review Instance Launch: Review the configuration details of your instance to ensure everything is set up correctly. You can make changes if needed.
Launch Instance: Once you're satisfied with the configuration, click the "Launch" button. AWS will prompt you to select or create a key pair for SSH access to your instance if you haven't already done so. Create and download the key pair.

Access Your Instance: Once the instance is launched, you can access it using SSH (for Linux instances) or Remote Desktop Protocol (RDP) (for Windows instances) using the key pair you downloaded. You'll need the public IP address or DNS name of your instance to connect to it.
Terminate Instance (Optional): When you're done with your instance, you can terminate it to stop incurring charges. Select the instance in the EC2 dashboard and choose the "Terminate" option. Be careful, as terminating an instance will delete all data stored on it.



These steps provide a general overview of the process. The exact steps and options may vary depending on your specific requirements and preferences.


