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

__Step 1: Create the Ticket in the OS-Ticket__ 
1. Log in to OS Ticket:
   - Navigate to the OS Ticket dashboard and create a new ticket
2. Ticket Details:
   - __Subject__: "Password Reset Request for Azure VM"
   - __Description__:
     - User Name: JohnDoe
     - Vm Name: AppServer-01
     - Issue: The user forgot their password and needs a reset
    - __Priority__: Medium

__Step 2: Reset Password via Azure Portal__
1. __Log in to Azure Portal__:
   - Go to Azure Portal and Login.
2. __Find the VM__:
   - Navigate to Virtual Machines and select AppServer-01
3. __Access Reset Password Feature__:
   - Go to __Operations > Run Command__
   - Select the __Reset Passsword__ option
   - Enter the username (JohnDoe) and a new password
   - Click __Run__ to execute the command
4. __Confirm Success__:
   - Notify the user of the new password and request they log in to verify success


__Step 3: Update Ticket__
1. __Resolution Details__:
   - Document the steps taken:
        - Reset the password using Azure Run Command
        - Provide the new credentials to the user
 2. __Close the ticket__
      - Mark the ticket as resolved and inform the user

<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h3>Issue 2: Enabling Permissions for a user</h3>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
