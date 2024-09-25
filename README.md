# OSticket-Lifecycle-Examples
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

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>

//Step 1: Update Departments
Change SysAdmins to Top Level: In the Admin Panel > Agents > Departments, change the SysAdmins department to a top-level department.
Delete Maintenance Department: Remove the Maintenance Department completely.

//Step 2: Create a Ticket as an End User
Log in as an end user at http://localhost/osTicket and create a ticket with the subject: "Entire mobile/online banking system is down."

//Step 3: Modify Ticket Properties as John
Log in as Help Desk Agent John at http://localhost/osTicket/scp/login.php.
Locate the ticket and set its properties:
SLA: Sev-A (1 hour, 24/7)
Department: Online Banking

//Step 4: Resolve the Ticket as Jane
Log in as Help Desk Agent Jane and access the ticket assigned to John.
Work through the ticket and mark it as resolved when complete.
</p>

![image](https://github.com/user-attachments/assets/7898f119-ba58-427c-bffd-f140e568df3b)


<br />

<p>
//Step 1: Create First Ticket as End User
Ticket Creation: Log in as an end user at http://localhost/osTicket and create a ticket:
Subject: "Accounting department needs Adobe upgrade, broken."

//Step 2: Modify First Ticket as John
Log in as Help Desk Agent (John): Access the ticket.
Observe Ticket Properties:
Check Priority
Check Department
Check SLA
Check Assigned To
Set Ticket Properties:
SLA: Sev-B (4 hours, 24/7)
Department: Support
Work the Ticket: Resolve the issue and mark the ticket as complete.

//Step 3: Create Second Ticket as End User
Ticket Creation: Create another ticket as an end user:
Subject: "CFO’s laptop will no longer turn on."

//Step 4: Modify Second Ticket as John
Log in as Help Desk Agent (John): Access the new ticket.
Observe Ticket Properties:
Check Priority
Check Department
Check SLA
Check Assigned To
Set Ticket Properties:
SLA: Sev-B (4 hours, 24/7)
Department: Support
Work the Ticket: Resolve the issue and mark it as complete.

</p>
<p>

![image](https://github.com/user-attachments/assets/e6b7bfd4-7211-47e0-bed6-9dc9c11c2f72)


</p>
//Step 1: Set Properties and Access
Set properties for all tickets, using SEV-A for the last ticket (SysAdmins). Note that after this, the ticket becomes inaccessible.
Switch to the admin panel to assign yourself view access to SysAdmins.

//Step 2: Observe Ticket Status
Return to the agent panel to observe the escalated ticket. Confirm that you can no longer make changes to it.

//Step 3: Solve Tickets and Email Notifications
Resolve all tickets. Explain that in most ticketing systems, including this one, every time you update a ticket, the user receives an email notification, allowing them to respond.

//Step 4: Ticket Intake and Best Practices
Discuss real-life ticket intake methods (phone, chat, email, web forms, or in-person requests). Emphasize the importance of creating tickets for all interactions, even for on-the-spot fixes, to maintain metrics.
Encourage further exploration of the system’s features, especially the email capabilities. Suggest practicing the lab multiple times to build confidence and technical skills.

<p>

![image](https://github.com/user-attachments/assets/a269bda5-d8d1-4779-be52-6179c45c8548)


</p>
<p>

<br />
