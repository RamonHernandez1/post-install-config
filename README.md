<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post configuration setup of the osTicket system .<br />

<p>

</p>
</p>
<p>
We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup.
first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. 
Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.
</p>
<img width="962" height="478" alt="Screenshot 2026-01-30 at 2 34 36 PM" src="https://github.com/user-attachments/assets/d5cf9f3a-a036-437f-a3a6-12305d4709b1" />

</p>
<br />
<p>
</p>
<p>
Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab. 
</p>
<br />
<p>
<img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create an Online Banking Team. 
</p>
<br />
<p>
<img width="962" height="746" alt="Screenshot 2026-01-30 at 2 42 05 PM" src="https://github.com/user-attachments/assets/3a4532a0-dfdd-46bb-bc14-f0c89d9e4b0b" />

</p>
<p>
Now that we have set up a new team, we will create a new setting that will allow anyone to create tickets. Go to Admin Panel->Settings->User Settings. Under authentication settings, make sure the box that says require registration and login to create tickets is unchecked.

</p>
<br />
<img width="959" height="710" alt="Screenshot 2026-01-30 at 2 57 01 PM" src="https://github.com/user-attachments/assets/af6499da-dc02-489d-8c24-e1c2f32925cd" />

</p>
<p>
Now we are going to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab. 
</p>
<br />
<img width="962" height="676" alt="Screenshot 2026-01-30 at 3 13 30 PM" src="https://github.com/user-attachments/assets/697474b2-c746-4ce3-a2f7-a15a71fbbb71" />

</p>
<p>
After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new. 
</p>
<br />
<img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking. 
</p>
<br />
<img src="https://i.imgur.com/kB7rts2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
