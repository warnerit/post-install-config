<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>


<p>
  
![image](https://github.com/user-attachments/assets/ad7d0dd6-6ef3-492c-8435-93e6dada261f)
</p>
<p>
We’ve successfully set up osTicket from scratch. Now, we’ll move on to system administration and post-installation configuration. The first task is to create new roles within the help desk system.
To begin, navigate to Admin Panel → Agents → Roles. Here, click on "Add New Role" to create a new role. Enter "Supreme Admin" as the role name. You can customize the permissions for any role, but since we’re creating a Supreme Admin, this role should be granted full access to all permissions.
Remember, roles define what actions agents are allowed to perform, so not all agents should be assigned unrestricted access.
If you've followed the steps correctly, your screen should now display the newly created "Supreme Admin" role, indicating that the setup was successful.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/1e6ed665-f5ca-4185-966e-58e56fa8c042)
</p>
<p>
Click on the "Departments" button under the Agents tab. This section allows you to create and manage departments within the help desk. Each agent is assigned to a specific department based on their role and responsibilities.
In this example, we’ll create a department called "System Administrators", which will be designated for the Supreme Admins.
Additional settings—such as SLAs, department managers, and email configurations—can also be managed from the Departments tab to further customize how each department operates.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/26c8a759-0b4e-4662-af78-902b70bda839)
</p>
<p>
Once the new department is configured, the next step is to set up a team. Teams allow you to group agents from different departments, enabling more flexible and specialized support structures. For instance, you might create an "A Team" made up of top technicians from various departments to handle high-priority issues.
You can also assign teams to specific help topics—such as products or services your organization offers—ensuring that inquiries are routed to agents with the right expertise.
To create a new team, navigate to Agents → Teams. By default, a Level I Support team is already created. In this example, we’ll create a new team called Level II Support to handle more advanced support requests.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/2bcb37f3-077f-4a84-8d47-4a9c7380db94)
</p>
<p>
Now it's time to create Agents. Agents are the helpdesk staff responsible for handling and resolving support tickets. Each agent is assigned a primary department and a primary role that determines their permissions for tickets routed to that department.
Agents can also be granted access to additional departments and may have different roles depending on the department they’re working in. You can configure an agent’s permissions, department access, and team membership under the Agents tab.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/6f9554c1-91c2-4b6c-81f5-6cf7f1db0f80)
</p>
<p>
Once you’ve created your agents, the next step is to add users. Users are the customers who submit support tickets when they encounter issues. Each user is identified by their email address.
To create a new user, go to Agent Panel → Users → User Directory → Add New.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/4b210757-851a-45ce-987a-6fb76c38d560)
</p>
<p>
SLA Plans define the expected time frame in which the help desk should resolve a ticket. To create an SLA Plan, navigate to Admin Panel → Manage → SLA Plans.
Each SLA Plan includes a schedule and a grace period—the time allowed to respond or resolve a ticket within that schedule.
For example, an SLA Plan named SEV-A might operate on a 24/7 schedule with a one-hour grace period for ticket resolution.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/6b2c2683-cfed-4893-a08c-20b212e96599)
</p>
<p>
Help Topics allow users to categorize their tickets, ensuring they’re routed to the appropriate department or team for faster resolution.
For example, you might create a help topic called "Business Critical Outage" to cover situations where customers are unable to access essential services like mobile banking.
</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/7a5a55a8-3131-435b-9a04-5248213d046f)
</p>
<br />
