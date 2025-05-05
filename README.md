<p align="center">

  ![image](https://github.com/user-attachments/assets/30d5c804-c3f0-438e-b517-215dcba3bbd4)

</p>

<h1>VPN - Prerequisites and Execution</h1>
This tutorial outlines the prerequisites and execution of Proton VPN.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- VPN client (Proton VPN)
  

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure (VM)
- Remote Desktop

<h2>Execution Steps</h2>

![image](https://github.com/user-attachments/assets/08f073ad-8536-4e22-8727-0676b6b34444)

![image](https://github.com/user-attachments/assets/201a0cd6-f794-44fb-afc6-614b0c3dadcb)

![image](https://github.com/user-attachments/assets/2d5e7922-34e0-464a-907d-3a5bc4d5a0a8)


Create a resource group in Microsoft Azure and name it accordingly. Following the resource group, create a VM in the Azure portal, entering the appropriate information. Copy the VMs public IP address and paste it into the Remote Desktop.


![image](https://github.com/user-attachments/assets/98726b25-6132-465f-951d-c61b1aadf28f)


On your own computer machine, navigate to https://whatismyipaddress.com/. This will disclose your current IP address for your personal machine. 


![image](https://github.com/user-attachments/assets/f2c1c32b-d3d2-46dc-a338-68bfba8b8bb3)


On the VM, navigate to https://whatismyipaddress.com and take note of the VMs IP address and location. This IP address reflects a non-VPN connection.


![image](https://github.com/user-attachments/assets/d0ebb3fc-e668-4c95-86cf-b2578884bfe6)


On your own computer create an account on Proton VPN (https://account.protonvpn.com/signup?plan=free&language=en). Once completed, on your VM, sign in to Proton VPN and download the VPN client to the VM. In this case, select "Download for Windows". Once downloaded click "Open file" and proceed through the prompts until you are able to select "Install". Sign in with your account credentials.


![image](https://github.com/user-attachments/assets/d8d1ca44-fffa-49df-aef7-f0f27885e2ae)

After logging in you should see a blue box at the top that says "Connect". This will automatically assign a VPN to the VM. If this option isn't showing, on the left-hand side of the screen there are countries available to choose from. Once a VPN is assigned, the VPN IP address will show at the bottom of the screen and the session traffic will begin to be displayed.


![image](https://github.com/user-attachments/assets/8cc44ce6-c263-499b-b3b9-6dbf764cb4d1)


Within the VM, navigate back to https://whatismyipaddress.com. There should be a new IP address displayed as well as the corresponding city and/or region that reflects the VPN IP address. It will also reveal that you are indeed using a VPN.








