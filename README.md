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
  - **Subject:** "Entire mobile/claim intake system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire claim intake system is down, preventing users from accessing their accounts.")

![image](https://github.com/user-attachments/assets/97a426e9-af2f-483a-8787-2fe547692d0e)

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
![image](https://github.com/user-attachments/assets/95234ab8-16bc-4f0c-8145-f77474b7f30c)

![image](https://github.com/user-attachments/assets/83460701-b156-4f6f-8842-0c39e7b91752)

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Claim Intake Team.

![image](https://github.com/user-attachments/assets/6d3b3d32-844d-476e-af6f-f5e09ede4c90)

![image](https://github.com/user-attachments/assets/cf15e90a-6f1c-49cd-8757-21e1c169398a)

![image](https://github.com/user-attachments/assets/c76f7750-ed27-43f9-b4ae-99a3300cebe2)

<h3>4.) Verify Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable.

<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/user-attachments/assets/11f30140-7834-4fc9-89cc-17e505edb64f)

---

<h3>6.) Create Another Ticket as End-User</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")
 
![image](https://github.com/user-attachments/assets/b30812d0-5b1b-4066-aec1-38e96649fad8)

<h3>7.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Admin (stephen)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
![image](https://github.com/user-attachments/assets/a202773c-4fce-4261-be10-19e7631d8a39)

<h3>8.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Assigned To:** Claim Intake
  - **Department:** Support.
 
![image](https://github.com/user-attachments/assets/f515f3a1-fb32-4ac8-908a-82e99b96e7ce)

![image](https://github.com/user-attachments/assets/0508def2-7154-4eee-b2ce-748abe8dcc94)

<h3>9.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/user-attachments/assets/e10e2d4d-a5e8-4290-9a0c-78a5c1a78bb2)

---

<h3>10.) Create a Final Ticket as End-User</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
  - **Subject:** "CFO’s laptop will no longer turn on"
  - **Details:** Describe the issue briefly (e.g., "The CFO's laptop is not powering on, and it needs urgent attention.")
 
![image](https://github.com/user-attachments/assets/431a0fcb-64ea-471d-882e-af6e7f3284df)

<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.

![image](https://github.com/user-attachments/assets/6dfbf93b-766f-4c4b-a08f-ebc4f8e6ef33)

<h3>12.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.
  - **Assigned To:** John Doe

![image](https://github.com/user-attachments/assets/122cebe1-e163-49e3-b8e6-6ea2c8e0bc16)

<h3>13.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated the lifecycle of a ticket from intake to resolution within osTicket. This lab highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
