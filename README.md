# post-install-config<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>
 
- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2 
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>
 
<p>
<img width="713" alt="Screenshot 2023-09-14 115013" src="https://github.com/gilbertramos/post-install-config/assets/140354494/0c0618b1-1357-41d4-9a40-74ae2ee0e8f6">
</p>
<p>
Now configure Roles by going to "Admin" to "Agents" then to "Roles".  Click on "Add New Role", next named it as "Supreme Admin".    "Add New Department"  "Add New Teams"
</p>
<br />
 
<p>
<img width="721" alt="Screenshot 2023-09-14 121735" src="https://github.com/gilbertramos/post-install-config/assets/140354494/c802a09f-ddcb-484a-9b13-4199f66ad46c">
</p>
<p>
To allow anyone to create Tickets I goto Admin Panel to Settings to User Settings.  Next make sure the box next to "Require registration and login to create tickets" is unchecked.  To configure Agents,  goto Admin Panel, to Agents to Add New.  The names John and Jane are used for the Agents in this case.  Now to configure Customers, I went to Admin Panel to Users to Add New.  The names Karen and Ken are used for the Customers in this example.
</p>
<br />
  
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next configure SLA goto Admin Panel to Manage to SLA.  There the SLA plan can be set for business hours, or 24/7 along with grace periods. Finally configure Help Topics by going to Admin Panel to Manage to Help Topics.  This will allow end-users to pick a Help Topic that best defines their situation.  Some Hlep Topic examples are Business Critical Outage, Personal Computer Issues,Equipment Request, Password Reset.
</p>
<br />
