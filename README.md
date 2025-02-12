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

<h2>Tickets</h2>

- Password Change Request
- Printer Connection Issue
- Software Installation Request
- Access Denied to Shared Drive

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

    
   



<h3>Issue 2: Printer Connection Issue</h3>

__Scenario:__ A user reports that they are unable to connect to the office printer and cannot print any documents.

__Step to Resolve:__ 
   1. __Check Printer Status:__
      - Verify that the printer is powered on, online, and connected to the network
      - Check for any error messages or warnings on the printer's display panel
   2. __Verify User's Device Configuration:__
      - Check the user's device to ensure the printer is installed and set the default printer
      - Reinstall the printer driver if it is missing our outdated
   3. __Run Troubleshooter:__
      - Run the printer troubleshooter on the user's device to identify and resolve common connectivity issues
      - Ensure the correct IP address or hostname is configured in the printer settings
   4. __Test Printing:__
      - Send a test print job to ensure the user can print successfully, If unsuccessful, escalate to the network or hardware team
  5. __Follow Up:__
     - Confirm with the user that printing is restored. Provide any necessary documentation or tips for future issues (how to reconnect to a network printer)
    
      



<h3>Issue 3: Software Installation Request</h3>

__Scenario:__ A user requests the installation of a specific software application on their workstation.

__Steps to resolve:__
1. __Validate Request:__
   - Confirm that the requested software is approved and licensed for use in the organization
   - Verify that there are sufficient licenses available for deployment
2. __Check System Requirements:__
   - Ensure the user's workstation meets the software's minimum hardware and OS requirements
   - Check for any conflicting software that needs to be removed before installation
3. __Install Software:__
   - Deploy the software via remote tools or manual installation, depending on organizational policies
   - Apply any unnecessary updates or patches after installation
4. __Verify Functionality:__
   - Launch the software and perform a quick test to confirm it works as intended. Provide the user with the necessary usage documentation
   - Verify with the user that it meets their requirements
5. __Provide Documentation:__
   - Share any available user guides or training materials with the user
   - Offer a quick overview of key features if needed
6. __Close the Ticket:__
   - Confirm with a user that the software is functioning properly and document the steps taken to complete installation
  
   




<h3>Issue 4: Access Denied to Shared Drive</h3>

__Scenario:__ A user reports they are unable to access a shared drive after being assigned to a new team.

__Steps to resolve:__
1. __Verify User Group Memberships:__
   - Confirm the user's current role and team assignment with their manager
   - Check if the user is part of the correct Active Directory (AD) group or permission level associated with the shared drive
2. __Update Permissions:__
   - If necessary, add the user to the appropriate AD group or assign direct permission through the shared drive settings
   - Document any permission changes made in the ticket for auditing purposes
3. __Refresh Uder Credentials:__
   - Instruct the user to log out and log back in to refresh their permissions
   - If using cached credentials, clear them and ensure the system pulls the updated permissions
4. __Test Access:__
   - Have the user attempt to access the shared drive
   - Provide a walkthrough on accessing the drive if needed
5. __Escalate if Necessary:__
   - If the issue persists, escalate to the file managment or network team with detailed notes on the troubleshooting steps taken
6. __Close the Ticket:__
   - Confirm with the user that the issue is resolved and document the solution in the ticket
  
   

 
