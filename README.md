<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
<h2>Description</h2>
This project focuses on configuring osTicket, so it can be used properly as a ticketing system. It consists of setting up multiple agents along with their departments, roles, and permissions. As well as, configuring SLAs (Service Level Agreements), help topics, and users.<br/>
<br/>


</p>
</p>
<p>
<h2>Environments and Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Virtual Machines</b>
- <b>Remote Desktop Connection</b>
- <b>osTicket</b>

</p><h2>Operating Systems Used </h2>

- <b>Windows 10</b>
<h2>Project Walk-through:</h2>
</p>With osTicket open navigate to the Admin Panel by clicking "Admin Panel" located in orange at the top right of the page:
<br />
<p>
</p>
<p>
<img width="798" height="576" alt="Screenshot 2026-02-10 at 7 14 34 PM" src="https://github.com/user-attachments/assets/0b2224e4-07f3-4404-aad3-599d14470a81" />

</p>To start configuring Roles Navigate to the "Agents" tab and click on "Roles" underneath the "Agents" tab. Enter a role name:
</p>
<p>
<img width="748" height="440" alt="Screenshot 2026-02-10 at 7 19 23 PM" src="https://github.com/user-attachments/assets/68fee407-e417-43dc-90d1-8f58652537fa" />

</p>
<p>
In the "Permissions" tab of this role, give this role all permissions in "Tickets", "Tasks", and "Knowledgebase". This will be our "Supreme Admin" Role:
<br />
<p>
<img width="963" height="710" alt="Screenshot 2026-02-10 at 7 23 56 PM" src="https://github.com/user-attachments/assets/5a72e582-d81d-41f8-bf89-e00c78a52e3e" />

</p>
<p>
To set up departments, while still in the "Agents" tab, click on "Departments" located just below the "Agents" tab. Name the department "System Administrators" and create the Department:</p><img width="1032" height="770" alt="Screenshot 2026-02-10 at 7 29 04 PM" src="https://github.com/user-attachments/assets/31746737-20a7-4af4-bf7b-948d3b77810a" />

</p>Next, create a team by selecting the "Teams" tab, while still in the "Agents" tab. Then, name the team "Online Banking" and create team:
<br /></p>
<img width="961" height="682" alt="Screenshot 2026-02-10 at 7 31 57 PM" src="https://github.com/user-attachments/assets/f0c32d2c-1afd-4078-9378-78d8fb588c27" />


</p>
<p>
Now, to allow anyone to create tickets, go to the "Settings" Tab, and under "Authentication Settings" make sure that "Require registration and login to create tickets" is unchecked:
</p>
<img width="959" height="688" alt="Screenshot 2026-02-10 at 7 35 15 PM" src="https://github.com/user-attachments/assets/bc1e2134-6167-4419-8369-f4d1bab2b926" />

</p>
<p>
To create agents (the help desk workers) navigate back to the "Agents" tab and select "Agents" and fill out the name, email, and username:
</p>
<br />
<img width="959" height="372" alt="Screenshot 2026-01-30 at 3 29 25 PM" src="https://github.com/user-attachments/assets/89d57047-ad1f-4703-aa5a-4f737f1a3c5f" />

</p>
<p>
SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period. 
</p>
<br />
<img width="961" height="692" alt="Screenshot 2026-01-30 at 3 33 57 PM" src="https://github.com/user-attachments/assets/9d15afff-84a8-4209-89a5-0aa318973540" />


</p>
<p>
Now we are going to configure help topics, for when users create a ticket. In the example below we have made a help topic for "Business Critical Outage" for example this can be if customers cannot access mobile banking. 
</p>
<br />
<img width="961" height="661" alt="Screenshot 2026-01-30 at 3 41 09 PM" src="https://github.com/user-attachments/assets/25977f4a-f99c-4ebe-8b5a-a08c08ba56d3" />

</p>
<p>
