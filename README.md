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

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

<h2>Lifecycle Stages</h2>

<h3>1.) Create Tickets as End-Users</h3>

- **Scenario 1:** Create a ticket as an end-user with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire online banking portal is down, preventing users from accessing their accounts.")

<img src="https://imgur.com/gEn5F1V.png" alt="osTicket logo"/>

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Admin (cristopher)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
<img src="https://imgur.com/17491yn.png" alt="osTicket logo"/>
<img src="https://imgur.com/fvyCybX.png" alt="osTicket logo"/>

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Team.

<img src="https://imgur.com/fvyCybX.png" alt="osTicket logo"/>
<img src="https://imgur.com/jUZFwGO.png" alt="osTicket logo"/>
<img src="https://imgur.com/CA1jgoL.png" alt="osTicket logo"/>

<h3>4.) Verify Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable.

<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<img src="https://imgur.com/SY0bbCt.png" alt="osTicket logo"/>
<img src="https://imgur.com/4Ox2Hsb.png" alt="osTicket logo"/>
<img src="https://imgur.com/kANvRzD.png" alt="osTicket logo"/>
<img src="https://imgur.com/UST0jzM.png" alt="osTicket logo"/>
<img src="https://imgur.com/oqNu9A3.png" alt="osTicket logo"/>

---

<h3>6.) Create Another Ticket as End-User</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")
 
<img src="https://imgur.com/weWurnV.png" alt="osTicket logo"/>

<h3>7.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Admin (cristopher)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
<img src="https://imgur.com/gN7Tir3.png" alt="osTicket logo"/>
<img src="https://imgur.com/skF8sLW.png" alt="osTicket logo"/>

<h3>8.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Assigned To:** Online Banking
  - **Department:** Support.
 
<img src="https://imgur.com/CA3taCk.png" alt="osTicket logo"/>
<img src="https://imgur.com/tEgEvIF.png" alt="osTicket logo"/>
<img src="https://imgur.com/515aOmA.png" alt="osTicket logo"/>


<h3>9.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<img src="https://imgur.com/wM0mZfw.png" alt="osTicket logo"/>
<img src="https://imgur.com/UFQcPfN.png" alt="osTicket logo"/>
<img src="https://imgur.com/14hagYx.png" alt="osTicket logo"/>
<img src="https://imgur.com/YDmgIo4.png" alt="osTicket logo"/>
<img src="https://imgur.com/VMrlQgR.png" alt="osTicket logo"/>
<img src="https://imgur.com/ZY33HEj.png" alt="osTicket logo"/>
<img src="https://imgur.com/6PTTRcr.png" alt="osTicket logo"/>


---

<h3>10.) Create a Final Ticket as End-User</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
  - **Subject:** "CFO’s laptop will no longer turn on"
  - **Details:** Describe the issue briefly (e.g., "The CFO's laptop is not powering on, and it needs urgent attention.")
 
<img src="https://imgur.com/BGgVM9a.png" alt="osTicket logo"/>


<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

<img src="https://imgur.com/4vWQLb3.png" alt="osTicket logo"/>
<img src="https://imgur.com/QbqbdQk.png" alt="osTicket logo"/>

<h3>12.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.
  - **Assigned To:** John Doe

<img src="https://imgur.com/jktspji.png" alt="osTicket logo"/>
<img src="https://imgur.com/NtqcfK5.png" alt="osTicket logo"/>

<h3>13.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<img src="https://imgur.com/lriwegk.png" alt="osTicket logo"/>
<img src="https://imgur.com/ihW13gb.png" alt="osTicket logo"/>
<img src="https://imgur.com/HRGu907.png" alt="osTicket logo"/>

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated the lifecycle of a ticket from intake to resolution within osTicket. Learning how to properly manage a ticket from intake to resolution helps you stay organized, work more efficiently, and ensure that customer issues are handled quickly and correctly. This lab highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
