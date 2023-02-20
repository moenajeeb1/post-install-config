<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial shows the post installatiion setup of osTicket system .<br />

<p>

</p>
</p>
<p>
We have successfully created osTicket and everything should be working in place. The first thing we will do is configure some roles and check to see the roles our ticketing system has already. Let's configure a new Supreme Admin role in the help desk. First go to the Admin panel-> Agents-> Roles.
Click on add new role then enter the name of the new role. We can edit the permissions of any role. We are creating a Supreme Admin role so we will asssign all permissions for this role. Roles are the permissions granted to agents per department that they have access to. Each role has a set of permissions that can be checked or unchecked for agents given their role in association with a department they have access to. An unlimited number of roles can be created and assigned to agents with access to various departments which we will go over shortly.
</p>
<img src=https://i.imgur.com/Q05Sl2s.png" height="80%" width="80%"/>
</p>
<br />
<p>
</p>
<p>
We will now create a new department in our ticketing system. We will be able to configure departments. We are already on the admin panel but we do this by going to Admin Panel -> Agents -> Departments. Agents are assigned to specific departments depending on their assigned role within the helpdesk. Go ahead and click on "add new department" and we will be creating the System Adminstrators department where the Supreme Admins will be in. The status of the department will determine its visibility as well as if tickets can be routed to that department.


</p>
<br />
<p>
<img src=https://i.imgur.com/KtIUwHm.png" height="80%" width="80%"/>
</p>
<p>
We can also create teams within osTicket for agents to be located in. Teams allow you to pull agents from different departments and organize them to handle a specific issue or problems. A good example of this is that you can create a help topic associated with a particular product you produce, and assign it to a team of agents located in different departments. We can set up a team by going to the Admin Panel -> Agents -> Teams. We will create a team called "level 2 support" since a level 1 support team was already created by default. 
</p>
<br />
<p>
<img src="https://i.imgur.com/fx4dFvm.png" height="80%" width="80%"/>
</p>
<p>
Let's now create a new setting that will esentially allow anyone to create tickets. We do this by going to Admin Panel->Settings->User Settings.
</p>
<br />
<img src="https://i.imgur.com/1p3tLQH.png" height="80%" width="80%"/>
</p>
<p>
Let's create some agents now! Agents are given access to the help desk with the intent to respond and resolve the tickets. Agents will need to be assigned to a primary department and will be given a main or primary role for the tickets given to that department. Agents can be given extended access to other additional departments as well and can have different roles of those departments. Agents have many permissions such as the ability to add new users, manage user information, delete users, etc. Let's add agents by going to Admin Panel -> Agents -> Add New Agents.
</p>
<br />
<img src="https://i.imgur.com/YerZCjN.png" height="80%" width="80%"/>
</p>
<p>
So now that we have just created our agents let's create some users on osTicket. Users are the ticket owners of the tickets that they create. Users are also known as customers and they create these tickets when they are having problems that need to be fixed by an IT professional. The users are associated with their E-mail address that uniquely identifies them. Create users by going to Agent Panel -> Users -> Add New User.
</p>
<br />
<img src="https://i.imgur.com/D1CXUbg.png" height="80%" width="80%"/>
</p>
<p>
Service Level Agreements known as SLA Plans, is esentially to provide a length of time in which a ticket needs to be closed. You have a certain amount of time to close a ticket created by a customer. You can create SLA Plans by going to Admin Panel -> Manage -> SLA. SLA Plans have a schedule and in that schedule there is a grace period which is the amount in hours before tickets with this SLA will become overdue if not closed in allotted time.
The example I have shown is SEV-B with a 4 hour grace period.
</p>
<br />
<img src="https://i.imgur.com/M73UWeu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics will help users to ensure the corrrect prompt response to the users ticket and categorize their tickets. They will also help determine what department it is going to and which agents will have access to them. In the example I have provided below I have created a help topic for "Personal Computer Issues" for customers experiencing certain issues they are not familiar with on their computer. 
</p>
<br />
<img src="https://i.imgur.com/PhH1pca.png" height="80%" width="80%"/>
</p>
<p>

