
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
1.Sign in to the AWS Management Console: Go to the AWS Management Console and sign in to your AWS account.

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/15af8b08-7531-413b-8b33-66f128eb89ca)



2. Navigate to EC2 Dashboard: By searching for it in the search bar in the AWS Management Console
   
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/d5ecde9b-9aae-46d3-a696-be53e1bb4630)
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/0e2cd3c7-1ff2-41b1-a605-a4aa251d804f)



   
3. Click instances then Launch Instance: Click on the "Launch Instance" button to start the instance creation process.
    ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/c633e305-c3b2-42c3-8931-b60dff2be054)
    ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/9620c9df-3e64-434d-9082-02b822d05737)


4. Name your virtual machine.Then choose an Amazon Machine Image (AMI): Select an AMI from the provided list. An AMI is a pre-configured template that contains the operating system and other software required for your virtual machine. You can choose from various Linux distributions, Windows Server, and other operating systems.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/56166bf0-1dbb-41ca-8461-5bd980d0512e)





5. Choose an Instance Type: Select the instance type that suits your requirements. Instance types vary in terms of CPU, memory, storage, and networking capacity. You can choose a general-purpose instance, compute-optimized instance, memory-optimized instance, etc.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/63c13f72-82de-4a4a-af69-370498956b35)


6. Configure Instance Details: Configure additional settings such as the number of instances to launch, keypair name (VPC, subnet, security groups), IAM role, monitoring options, and more.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/140c4722-0603-4665-b2e8-ad81f8595a92)

- Click Create new key pair
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/71aad0a2-6189-414e-b669-b2172a270952)
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/5b3bf9af-3c18-4af1-877c-6aad35486bad)
-After you have created your key pair you should see it in your downloads folder
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/2d1eef42-ceb5-4e77-abe6-2b4a26eb4f07)



8. Add Storage: Specify the storage requirements for your instance. You can add additional volumes if needed and choose the type of storage (e.g., SSD, HDD) and its size.
Configure Security Group: Define security group rules to control the traffic to your instance. You can specify inbound and outbound rules to allow traffic based on protocols, ports, and IP addresses.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/c25428b5-f78d-4b49-b05a-27a34f8ed25c)
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/ccb72bee-f2a2-49f7-8b00-4eec3d9d8400)


9. Review Instance Launch: Review the configuration details of your instance to ensure everything is set up correctly. You can make changes if needed.
Launch Instance: Once you're satisfied with the configuration, click the "Launch" button. AWS will prompt you to select or create a key pair for SSH access to your instance if you haven't already done so. Create and download the key pair.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/7e82a70e-9137-4816-802c-2abf920397a3)



10. You should see success which means your virtual machine was created. Access Your Instance: Once the instance is launched, you can access it using SSH  or Remote Desktop Protocol (RDP) (for Windows instances) using the key pair you downloaded. You'll need the public IP address or DNS name of your instance to connect to it.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/cc23599d-5224-404a-8284-ba95d38570bd)

11. To connect to your virtual machine click the box next to the name of your VM. Then Click connect. Click RDP Client. After click Download remote desktop file and you should see your virtual machine show up in your browser download tab.

- ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/5379343c-83f8-4970-ab06-c8f727406348)
 - ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/5066ddee-5f12-45d6-9ff6-c7b2709bef76)
-  ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/aad5b610-4469-40e0-8fdd-3d4b9474633f)

 12.To get the password click get password and it should take you to the next page. Then click upload private key and select the one you created earlier. AFter click decrypt password. Then Select copy password.
 ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/4785d5a7-1e45-4498-a5d4-cc739e2f7c80)
 ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/13af8951-94a2-4448-9225-85b5ce46591a)
 ![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/f34a7c25-ade1-44dd-999a-20f76cbd53eb)

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/dd72ce6e-14ed-4f10-b186-3840dacf38df)
-----------

13.Double click your RDP connection then paste your password. Then click OK.Next you'll click Yes and you will now have created your virtual machine.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/63cd7522-d326-4255-883e-708f89b628e5)


![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/f2e5066b-0237-492b-96c9-0c3380449e8f)
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/8f742758-a3a4-46e2-815e-1d6899787de9)

![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/4c0e1c91-6e2f-43a7-88e6-2d8e6a440cce)

14.Terminate Instance (Optional): When you're done with your instance, you can terminate it to stop incurring charges. Select the instance in the EC2 dashboard and choose the "Terminate" option. Be careful, as terminating an instance will delete all data stored on it.
![image](https://github.com/PeterCodyLeon/Creating-virtual-machines-in-AWS/assets/161895166/415881b4-8d4c-4b0a-8136-e79a3287fb05)



These steps provide a general overview of the process. The exact steps and options may vary depending on your specific requirements and preferences.


