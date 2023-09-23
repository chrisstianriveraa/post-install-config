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

- Role
- Departments
- Adding Agents
- Users
- SLA Plan 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/wXM9pcJ.png"/>
</p>
<p>
Great! Lets get straight to it. This here is what roles  I created for the system. In order to do this first we go to Admin panel-> Agents-> Roles. We would create a Supreme Admin, click on 'Add new role" then input the name of the new role. You can modify any specific roles permission, since we created  Supereme Admin they will be given all permissions. Also remember not all agents will be given unlimited access. 

</p>
<br />

<p>
<img src="https://i.imgur.com/cJWIYrl.png"/>
</p>

<p>
Here we have the Departments. You can get here by clicking on the agents tab then click departments. Every agent is assigned a depeartment, in this case since we created a Supreme Admin, we will create a "System Administration" department. Specific things like SLA's and other email settings can be set up in the departments tab.


</p>
<br />
<img src="https://i.imgur.com/RLMvRRO.png"/>
<p>
Below here, we created a new agaent. Agents are the employees of the helpdesk team, they are the ones solving tickets. Agents will be given specific departments and given primary roles for tickets specific to those agents.  Permissions, access, and teams are assigned in the Agents tab.
</p>
<img src="https://i.imgur.com/4tEg8b2.png"/>
<p>
After creating agents, we will create users. Users are customers or end users that create tickets when they may be facing issues. To create a user we first go to Agent Panel-> Users-> User Directory-> Add new.
</p>
<img src="https://i.imgur.com/ebH7Tbr.png"/>
<br />

<p>
SLA Plans provide a time frame of which the help desk is expected to solve said specifc ticket. SLA Plans are created by going to the Admin Panel->Manage->SLA. Each SLA Plan can have a schedule and within that schedule there is a grace period. In the example below SEV-A has scheduel of 24/7 with a grace period fo an hour.
</p>
<img src="https://i.imgur.com/lkVeLP4.png"/>
