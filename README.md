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

- Ticket Creation
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>


![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/dde4c020-5203-43a5-bbb3-61b53ecfe86e)
<p>
To start creating a ticket as a user, go to http://localhost/osTicket/ and click on "Open a New Ticket”.
</p>
<br />

![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/b64e55be-ca66-4c01-9324-10e60f0b90e9)
<p>
For this tutorial, we will use Karen Smith (a user we created earlier) as our end user. Enter Karen’s name (Karen Smith) and email (karen@osticket.com). For the Help Topic, choose Business Critical Outage. In the Issue Summary field, type something similar to “Entire mobile online banking is down”. In the field below that, write a more detailed explanation of the issue, such as “Customers are reporting they are getting a 404 error when browsing to online banking”. Then click on “Create Ticket”
</p>
<br />

![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/86cbbe00-a9bc-4165-ac98-de1b49e2f59e)
![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/345362b9-9e33-4030-a05a-f7c9cded538c)
<p>
First, log in as Jane Doe (jane.doe) through osTicket's Agent portal at http://localhost/osTicket/scp/login.php. You should see the tickets that were created by users.
</p>
<br />

![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/47446314-5edb-433e-92a5-f9ffab442be3)
![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/369ffae3-ce19-44a2-a564-6fb7a6567e52)
![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/f7132ea7-f5d3-4c44-9322-91866c89076e)
![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/cf0a30d8-b1fc-4bb7-a02b-f5ad657af09c)
<p>
Navigate to Karen Smith’s ticket titled “Entire mobile online banking is down”. Due to the severity of the issue, set the Priority to Emergency and add “Business Impacting Event” to the notes. Adjust the SLA Plan to SEV-A and include “Business Impacting, Critical Incident” in the notes. Change the Department to System Administrators and add “Sys Admins responsible for mobile banking infrastructure” to the notes. Finally, assign this ticket to Jane Doe.
</p>
<br />

![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/43c79fdf-a753-44ef-a0d6-c20d05ad235b)
<p>
As the agent responding to our hypothetical ticket scenario, Jane Doe writes the following reply: "Coordinating with the Sys Admins team to restore mobile banking services." Leave the Ticket Status as Open and click Post Reply.
</p>
<br />

![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/418b72db-0bef-4295-b01e-3685912d4fef)
![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/4d4b9128-830c-4683-b2e2-34d26718ccd5)
<p>
Continuing our hypothetical scenario, the System Engineering Department has resolved the critical mobile banking issue. Return to Karen’s ticket titled “Entire mobile online banking is down” and provide the following update: "Jerry from Sys Engineering identified and fixed a failed load balancer. Mobile banking services should now be restored." Change the Ticket Status to "Resolved" and click on Post Reply.
</p>
<br />

![image](https://github.com/jamstylr/ticket-lifecycle/assets/159660523/e73223a2-6b42-4fdc-9c50-165add8bb191)
<p>
When you return to the Open Tickets section, you'll notice that Karen's message has disappeared, now listed in the Closed Folder.
</p>
<br />
