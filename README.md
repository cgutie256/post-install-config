<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles for grouping permissions
- Create a new Department
- Create a new Team
- Configure Agents
- Create Users
- Configure SLA
- Create Help Topics for users to categorize their issues

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/61e29d1d-6af9-4b21-94f9-ab77f8b04b07" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Start by logging into the admin panel of osTicket.  


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/f811223e-b1eb-443a-af5c-ab0cd8af95af" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Once you have logged in, navigate to the roles tab by clicking on Agents, then Roles.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/7663100f-3b28-44bd-8c0f-b7ad8d50c437" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click Add a new role, the name will be Supreme Admin, go to the permissions tab, and make sure everything is checked.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/1d74387e-c6b6-408a-8635-e3b27b15078f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click Create Role, and that will generate the new role.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/549b154f-1727-4332-b0f0-8e5c90e1184f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Next we will configure the departments. 


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/72a314c9-fc9f-4ae8-85bf-657d9aca1497" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Click Add New Department and set up a top-level department. Name it SysAdmins and leave everything else as the default.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/04874998-72a3-48b1-a192-e17794c586fe" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Now we’re gonna create a new team. Call it Online Banking and leave the rest of the settings as-is.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/f6e17600-a4f9-48e0-a980-ec4dbc708391" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Let’s create a user named Jane Doe. Set a password you’ll remember, then under the Access tab, make Jane a Supreme Admin in the SysAdmins department. Once that’s done, head over to the teams section and add Jane doe to the Online banking team.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/e346dfe6-6897-4d82-958a-f6f818459c74" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Now let’s add a user named John Doe. Set a password you’ll remember, make him a view only user in the Support department, and leave everything else as-is.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/f1678acd-d6fd-4132-8077-1c2d6b8d67fa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Next, we’re heading over to the Agent Panel where we are going to create a user from there.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/f28dd862-c3a3-40ba-8ff7-c538e4badc4a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
We will create a user named Karen.


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/88b7f912-954d-4c14-a3a3-8d3605d36cc1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Now we’re gonna set up 3 different SLAs. Head back to the Admin Panel, then go to the Manage tab, and click on SLA. We’ll create the following SLAs:
</p>

- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)


</p>
<p>
<br />
<img src="https://github.com/user-attachments/assets/4708589e-93d8-45c9-86aa-654f398563d7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Finnally we will create 5 help topics to give users options when making help tickets. </p>
</p>

- Business Critical Outage (Report a Problem)
- Personal Computer Issue (Report A Problem)
- Equipment Request (General Inquiry)
- Password Reset (Report A Problem)
- Other (General Inquiry)

<br />
<p>That’s it for the post-install setup—you're now ready to start submitting and working on tickets!</p>

