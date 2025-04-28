<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This guide outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.  The goal of this project is to familiarize IT professionals with the ticketing process and the layout of a ticketing application.

<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites</h2>

- If you haven't installed or configured osTicket yet on your machine, please refer to the following:
  - <a href="https://github.com/cristopherb19/osTicket-prereqs">osTicket: Prerequisites and Installation</a>
  - <a href="https://github.com/cristopherb19/osTicket-post-install-config">osTicket: Post-Installation Configuration</a>

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<h3>&#9312; Intake</h3>

<p>

- The intake is the first step in the ticket lifecycle
- A user(in this case, Ken) that needs help will create a support ticket
  - NOTE: The user is not always the one to create a ticket.  An instance when this might occur is if someone calls you with an issue, and you(the support agent) will create a ticket on their behalf
<img src="https://i.imgur.com/Wl0nYZ6.png" height="80%" width="80%" alt="New Ticket"/>

</p>
<br />

<h3>&#9313; Assignment and Communication</h3>

<p>

- Support Agent(John Doe) logs in and looks to see if there are any open tickets for him to work on
<img src="https://i.imgur.com/3OBlIh8.png" height="80%" width="80%" alt="Open Ticket"/>

- Support agent(John Doe) reads the ticket and assesses the issue
- If ticket is unclear on the severity of the situation, support agent(John Doe) will message the user(Ken) to gather more information so he could make an informed decision on how to proceed
- Support agent(John Doe) will then update the SLA(Sev-A, Sev-B, Sev-C, etc) and assign either himself, another agent, or another department to work the ticket to resolution
<img src="https://i.imgur.com/bgn9FRO.png" height="80%" width="80%" alt="Ticket assignment"/>
  
</p>
<br />

<h3>&#9314; Working the Issue</h3>

<p>

- While working the issue, support agent(John Doe) should constantly be updating the ticket thread with troubleshooting that has been done, and any new information that has been obtained
<img src="https://i.imgur.com/agqPTqr.png" height="80%" width="80%" alt="Ticket thread"/>
  
</p>
<br />

<h3>&#9315; Resolution</h3>

<p>

- At this point, the issue has been addressed and a solution has been implemented
- The support agent(John Doe) will now confirm with the user(Ken) that the issue has been resolved after the implementation of the solution
- If the solution presented by the support agent(John Doe) does not fix the issue, then the support agent(John Doe) will go back to troubleshooting and working the issue to find another solution
- Once confirmed that the solution works, support agent(John Doe) will now document any details that have not already been noted, then set the ticket status to "Closed"
<img src="https://i.imgur.com/hX17qKk.png" height="80%" width="80%" alt="Closed tickets"/>
  
</p>

<h2>Final Thoughts</h2>

<p>

This project serves as the foundation for what any IT professional that works tickets will do on a daily basis.  There will be many different scenarios that will occur on the job, but the structure and steps taken to resolve each ticket will generally be the same.  Hopefully this project helps you better understand the lifecycle of a ticket and what you can expect when working a job in this role.

</p>

<h2 align=center>Thank you and good luck on your future endeavours! 🎉</h2>
