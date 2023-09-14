<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.  <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles and Departments
- Configure Teams and Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>

![284224BB-CCC5-4FF5-B4D0-FCBC71DFFF96](https://github.com/dblock5/post-install-config/assets/102873312/d934e60c-33a3-4761-be00-b4084b8dcad7)

![88886E0C-4DF7-4F60-B67C-892C431A8118](https://github.com/dblock5/post-install-config/assets/102873312/278dee06-c16e-4548-818f-3bf7078c7132)

![0EE24742-BA2E-48DF-B802-7530B9B08429](https://github.com/dblock5/post-install-config/assets/102873312/e37bc572-b2b2-4f05-af6c-8dcb402cc289)

</p>
<p>
First, I created and configured roles. Which are permissions granted to agents per department that they have access to. I went on the Admin Panel, clicked agents, then roles, and then added a new role called admin. Then granted admin permissions to do anything such as deleting tickets and creating tickets etc. Then I created a new department. I clicked admin panel, agents, then departments. Then I added a new department called System Administrators 
</p>
<br />

<p>
<img width="745" alt="image" src="https://github.com/dblock5/post-install-config/assets/102873312/0e632050-f07d-492b-8805-5327716b9ec3">

![047A3133-A3D1-42EE-B989-DF467120C299](https://github.com/dblock5/post-install-config/assets/102873312/99bbddee-98d1-4fda-a607-7aed89bfbca9)
</p>
<p>
Then I created different teams. In osTicket teams allows you to pull agents from different departments and organize them to handle a specific problem. I went on the admin panel, agents, then clicked teams. Then I created a new team called Level II Support, and assigned an agent to the team, and created some agents. On the admin panel, clicked agent panel and added a couple of agents and assigned them to different departments and added them to a team.
</p>
<br />

<p>
<img width="850" alt="image" src="https://github.com/dblock5/post-install-config/assets/102873312/c55176f9-e588-4f80-9bc6-827320b2e9cb">

</p>
<p>
Then I created some users (customers). I clicked on agent panel, then users, and added a couple of new users. 
</p>
<br />
<img width="689" alt="image" src="https://github.com/dblock5/post-install-config/assets/102873312/e4b64bbc-3ef1-4a61-8f02-6bf973480f26">

<img width="691" alt="image" src="https://github.com/dblock5/post-install-config/assets/102873312/280bc1c2-cc2f-4aa0-8938-3fa140d60a89">

<p>

</p>
<p>
Then I configured SLA's. In osTicket SLA is defined as a time limit for how long ticket will be open. I went on the admin panel, went to manage, and clicked SLA. Then I added different SLA plans with different grace periods and time schedules. 
</p>
<br />

<p>
<img width="689" alt="image" src="https://github.com/dblock5/post-install-config/assets/102873312/ccf04bbc-42af-4cdb-8b66-c488709b7e0c">

</p>
<p>
Then I created different Help Topics. When the users are filling out different tickets they can choose different Help Topics for what they need help with. For example password resets, login issues etc. On admin panel, I clicked manage, then Help Topics. Then I created different Help Topics such as password reset. 
</p>
<br />
