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
<a href="https://imgur.com/4Sde5Mg"><img src="https://i.imgur.com/4Sde5Mg.png" title="source: imgur.com" /></a>
</p>
<p>
To start this lab we will open the End Users link in a new tab and create some tickets as Karen and Ken. Click open new ticket and add these tickets. 
  
  
1-Entire mobile online banking system is down

  
2-Accounting department needs adobe upgrade

  
3-When are we getting a hardware refresh

</p>
<br />

<p>
<a href="https://imgur.com/VL4dZlT"><img src="https://i.imgur.com/VL4dZlT.png" title="source: imgur.com" /></a>
</p>
<p>
  
Now we will login as an jane doe(jane is the agent that we created is the post installation setup lab). We will assume jane as a helpdesk worker who will login and solve her everyday tickets

</p>
<br />

<p>
<img src="https://i.imgur.com/OqaUlWz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Jane will open the first ticket which says entire mobile banking is down. We are supposing that here jane will work as both the helpdesk technician and the que manager. Start the process by setting the SLA. Since this problem involves a business, set the SLA to SEV-A.

</p>
<br />

<p>
<a href="https://imgur.com/sIddYaK"><img src="https://i.imgur.com/sIddYaK.png" title="source: imgur.com" /></a>
</p>
<p>
Change the department of the ticket from support to System administrator has the all permissions to do everything.
  
Change the priority level from normal to Emergency.
</p>
<br />

<p>
<a href="https://imgur.com/PXsYmBg"><img src="https://i.imgur.com/PXsYmBg.png" title="source: imgur.com" /></a>
</p>
<p>
These are the threads and as jane is making changes and adding comments, we can see them. The system administrator in this scenario is responsible for mobile banking. Jane will coordinate with them to bring the mobile banking back online.

</p>
<br />


<a href="https://imgur.com/lEOabPo"><img src="https://i.imgur.com/lEOabPo.png" title="source: imgur.com" /></a>
</p>
<p>
Jane is collaborating with Jerry from Sys Engineer, where he highlighted and corrected the issue.

</p>
<br
<p>


<p>
<a href="https://imgur.com/MQWlVVo"><img src="https://i.imgur.com/MQWlVVo.png" title="source: imgur.com" /></a>
</p>
<p>
The thread is now updated, showing the messages from the collaboration between Jane and Jery which is logged in the Ticket.
</p>
<br />

<p>
<a href="https://imgur.com/hLpmYWn"><img src="https://i.imgur.com/hLpmYWn.png" title="source: imgur.com" /></a>
</p>
<p>
The ticket Jane resolved is removed from "Open Tickets" and will now appear under "Closed Tickets"
</p>
<br />

<p>
  <a href="https://imgur.com/aS0o9yk"><img src="https://i.imgur.com/aS0o9yk.png" title="source: imgur.com" /></a>
</p>
<p>
  When tickets are resolved, they now appear under the "Closed Tickets" section of osTickets.
</p>
<br />

Hope you enjoyed this tutorial!
