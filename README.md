-<img src=https://i.imgur.com/rEqOMzN.jpg/>
# Creation of a Virtual Machine on Microsoft Azure
In this walkthrough we will create a Windows 10 Pro virtual machine on Microsoft Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- <img src=https://i.imgur.com/q300eUb.png/>
- Create A free Microsoft Azure Account at https://azure.microsoft.com/en-in/free/ 
- Click on the start free and then click on No account Create one.
- 
- Step 2
- <img src=https://i.imgur.com/6NfHbdi.png/>
- At create account, enter your email address and password and verify your email address by entering the code that is sent to you.
- Step 3
 
- <img src=https://i.imgur.com/YLw5O3t.png/>
- <img src=https://i.imgur.com/RJWDoWV.png/>
- <img src=https://i.imgur.com/C3Ih2fF.png/>
- Once your email address has been verified, enter your personal information along with your credit card information. Click on Sign up once you have given the information.  You will be given an Azure Subsciption 1 account with 200$ worth of service.

- Step 4

-<img src=https://i.imgur.com/iQMMNq8.png/>
- Congradulations, you now have an Microsoft Azure account. Click on the Microsoft Azure link to bring you to the home page.

- Step 5

- <img src=https://i.imgur.com/HadHedV.png/>
- <img src=https://i.imgur.com/7uVro3F.png/>
- Now click on Resource group and click on Create.

- <img src=https://i.imgur.com/lpgyqmq.png/>
- Choose a name for the Resource group for example "Rsch1".
- Choose the region that is closest to you.
- Now click review and create.
- Step 6

- <img src=https://i.imgur.com/Jini4iR.png/>
- Once the resource group has been created, click on the Microsoft Azure link and  Click on Virtual Machine. Click create and choose Azure Virtual Machine.
- <img src=https://i.imgur.com/M2HpRgA.png/>
      
- For Resource group choose Rsch1.
- Choose a name for the Virtual Machine for example "VM1".
- The region will match the same region you chose for resource group Rsch1.
- For Image we will choose Windows 10 Pro, Version 21H2.

- <img src=https://i.imgur.com/JFnUxcY.png/>
- For Size choose Standard_B1s-1vcpu, 1GiB memory.
- For administrator account choose a Username and Password and confirm the password.  This will allow you to enter and use the virtual machine VM1.  Be sure to note it down.  

- <img src=https://i.imgur.com/tW9Nwnb.png/>
- Click on Licensing and click on Review and create.

- <img src=https://i.imgur.com/yrahcH0.png/>
- Once it has been validated, click create.
- Step 7

- <img src=https://i.imgur.com/6sc3jxh.png/>
- Once deployment is complete.  You now have a virtual machine. Click on "go to resource" and inspect your new virtual machine
