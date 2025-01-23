<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Password Change Request
- Enabling Permission for a user
- 
- 

<h2>Lifecycle Stages</h2>


<h3>Issue 1: Password change request</h3>

__Scenario:__ A user requests assistance in changing their login password for a company system or application.

__Step to Resolve__ 
1. __Verify User Identity__
  - Confirm the identity of the user by asking for security verification (answering security questions or confirming details like employee ID or email).
2. __Access User Account Settings:__
   - Navigate to the user management (Active Directory or the specific application's admin console)
   - Locate the user's profile
3. __Reset Password or Provide Password Change Option:__
   - if the system allows for domain resets:
        - Reset the password to a temporary one and provide it to the user securely
   - If the user can change the password themselves:
        -  Guide them to the password reset functionality(via the Forgot Password link)
4. __Enforce Security Policies:__
   - Ensure the new password complies with the organization's policy
5. __Test and Verify:__
   - Have the user log in with the new password to confirm access
   - Instruct them to update any stored credentials on other devices, like email clients or mobile apps
6. __Document the Resolution:__
   - Log the ticket with details of the action taken (password reset date, verification steps) and close the ticket.
   

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Issue 2: Issues with Printer</h3>

__Scenario:__ A user reports that they are unable to connect to the office printer and cannot print any documents.

__Step to Resolve:__ 
   1. __Check Printer Status:__
      - Verify that the printer is powered on, online, and connected to the network
   2. __Verify User's Device Configuration:__
      - Check the user's device to ensure the printer is installed and set the default printer. If not, add the printer using its IP address or hostname
   3. __Run Troubleshooter:__
      - Run the printer troubleshooter on the user's device to identify and resolve common connectivity issues
   4. __Test Printing:__
      - Send a test print job to ensure the user can print successfully, If unsuccessful, escalate to the network or hardware team 


<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Software Installation Request</h3>

__Scenario:__ A user requests the installation of a specific software application on their workstation.

__Steps to resolve:__
1. __Validate Request:__
    Confirm that the requested software is approved and licensed for use in the organization
2. __Check System Requirements:__
   Ensure the user's workstation meets the software's minimum hardware and OS requirements
3. __Install Software:__
   Deploy the software via remote tools or manual installation, depending on organizational policies
4. __Verify Functionality:__
   Launch the software and perform a quick test to confirm it works as intended. Provide the user with the necessary usage documentation


<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
