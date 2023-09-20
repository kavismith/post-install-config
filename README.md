


<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. We will be working as an Admin, who sets up the ticketing system and defines the roles and other administrator duties.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Roles
- Create Departments
- Create Teams
- Allow anyone to create a ticket
- Create Agents
- Create Users
- Create SLA''s
- Create Help Topic

<h2>Create Roles</h2>


![image](https://github.com/kavismith/post-install-config/assets/143667203/37246ada-bb18-4d8d-9699-ebf28abaaed8)

</p>
<p>
To create a role called "Supreme Admin," which grants the user the ability to create tickets, delete tickets, and assign tasks to agents or teams, follow these steps:
  Begin by accessing the Admin Panel on the platform.

- In the Admin Panel, navigate to the "Agents" section.
- From there, proceed to the "Roles" subsection.
- To initiate the creation of the new role, click on the option to "Add a New Role."
- In the provided field, name the role "Supreme Admin."
- After naming the role, the next step is to assign the necessary permissions to it.
- Carefully select all the permissions that should be associated with the "Supreme Admin" role. This should include permissions related to working on tickets and tasks.
By completing these steps, you will successfully create a role called "Supreme Admin" with the specified permissions, allowing individuals in this role to create tickets, delete tickets, and assign tasks to agents or teams as needed.
</p>
<br />

<h2>Create Departments</h2>

![image](https://github.com/kavismith/post-install-config/assets/143667203/55c1db44-a4a0-496a-a724-a03ed91f60a2)

To configure departments for ticket assignment, follow these steps:

- Begin by accessing the Admin Panel on the platform.
- In the Admin Panel, navigate to the "Agents" section.
- Within the "Agents" section, find and click on the "Departments" option.
- To create a new department, select the "New Department" option.
- In this example, let's name the new department "System Administrators."
- For this practice, you can retain all the default settings for the department.
Optionally, you have the flexibility to go in and further customize the department. This can include assigning a manager, setting up SLAs (Service Level Agreements), specifying whether the department should be private or public, and even adjusting outgoing mail settings.

![image](https://github.com/kavismith/post-install-config/assets/143667203/7c6a3d83-39e5-4d40-873b-c74590609f72)

By completing these steps, you will have configured a new department called "System Administrators," and you can further tailor its settings based on your specific needs. Departments play a crucial role in ticket assignment, ensuring that customer or team member issues are directed to the appropriate teams for resolution.

</p>
<p>
  
</p>
<br />

<h2>Create Teams</h2>

![image](https://github.com/kavismith/post-install-config/assets/143667203/5d57214c-2070-42a8-9320-b50e57f2938a)
The Teams feature provides the capability to assemble agents from various departments to address specific tickets or address particular issues efficiently. Additionally, you can designate a team lead who will receive notifications on behalf of the team. To access the Teams feature and establish a new team, follow these steps:

- Start by navigating to the Admin Panel within the platform.
- Within the Admin Panel, go to the "Agents" section.
- In the "Agents" section, locate and click on the option for "Teams."
- To create a new team, select the "New Team" option.
- In this example, let's name the new team "Level II Support."
- You can then proceed to choose the members you wish to include in this team, ensuring that it consists of the appropriate agents for the task at hand.

![image](https://github.com/kavismith/post-install-config/assets/143667203/b3c4c8a9-2cf6-47b7-a886-7fcdaa0ba7b7)

By following these steps, you will effectively utilize the Teams feature, enabling you to form specialized groups of agents for addressing specific tickets or issues, with the added option of designating a team lead to receive notifications on behalf of the team.

</p>
<p>

</p>
<br />

<h2>Allow Any One To Create Tickets</h2>


![image](https://github.com/kavismith/post-install-config/assets/143667203/e438523e-95c6-4638-800f-a3f1b4a91cf4)


</p>
<p>
To enable ticket creation for all users, follow these steps:

- Start by accessing the Admin Panel within the platform.

- Within the Admin Panel, go to the "Settings" section.

- In the "Settings" section, locate and select "User Settings."

- Ensure that the option for "Required Registration and Login to Create Tickets" is unchecked.
  
By completing these steps, you will allow anyone to create tickets without requiring mandatory registration and login, streamlining the process for users to submit their concerns or issues.
</p>
<br />

<h2>Create Agents</h2>
  
![image](https://github.com/kavismith/post-install-config/assets/143667203/49789ff9-b98e-480c-a32d-6650ceffbf93)

Agents are integral to the ticket management process as they handle and resolve tickets. Each agent belongs to specific departments and is assigned specific roles, and administrators have the ability to reset agent passwords. To add a new agent, follow these steps:

- Begin by accessing the Admin Panel within the platform.

- Inside the Admin Panel, go to the "Agents" section.

- To add a new agent, select the "Add New" option.

- In this example, let's name the first agent "Jane Carter." Her email address is "jane.carter@osticket.com," and her username will be "jane.carter."

![image](https://github.com/kavismith/post-install-config/assets/143667203/d2acc3f6-cc8e-4b7d-b017-cf95befb0bc6)

Additionally, assign Jane Carter to the primary department, which is "Maintenance," and grant her all-access permissions.

![image](https://github.com/kavismith/post-install-config/assets/143667203/1ef46656-8999-44b2-97b9-913ea0810399)

Now, create another agent named "John Smith." His email address is "john.smith@osticket.com," and his username will be "john.smith."

![image](https://github.com/kavismith/post-install-config/assets/143667203/4fa26003-a442-4cd0-862d-9bbc08d425b9)

Ensure that John Smith has access to the "Supreme Administrator" role and is designated as a "Supreme Admin."

![image](https://github.com/kavismith/post-install-config/assets/143667203/a476d19c-9de7-4837-aba3-cba565d295e7)

Set a Password for each Agent.
</p>
<p>
</p>
<br />

<h2>Create Users</h2>

Users have the ability to create accounts for signing in and generating tickets. The User Directory feature facilitates agents in searching for tickets associated with specific users. Furthermore, users can be added to or removed from the User Directory directly from the Agent Panel. To access the User Directory, follow these steps:

- Access the Agent Panel within the platform.

- Inside the Agent Panel, navigate to the "Users" section.

- To add new users to the User Directory, select the "Add New Users" option.

![image](https://github.com/kavismith/post-install-config/assets/143667203/2b230105-3130-4c01-9cdf-cd8142d6faff)

The first user will be named "Karen Karen" with the email address "Karen@osticket.com."

![image](https://github.com/kavismith/post-install-config/assets/143667203/38064188-15af-455f-9930-672407491a33)

Following that, the second user will be "Ken Ken" with the email address "ken@osticket.com."

Once created, these users will then be added to the User Directory, where they can be managed for ticket management and support purposes.


</p>
<p>

</p>
<br />


<h2>Create SLA's</h2>

To establish Service Level Agreements (SLAs) that define specific timeframes for ticket resolution expectations, follow these steps:

First, access the Admin Panel within the platform.

Within the Admin Panel, select the "Manage" option.

Next, click on "SLA" and then choose the "Add New SLA Plan" option.

![image](https://github.com/kavismith/post-install-config/assets/143667203/888520cd-05a6-4008-9e7e-c5cefeab843b)

Name the first SLA "SEV-A." Set the schedule to "24/7," indicating that if a SEV-A ticket is created on a Saturday at 10 am, it should be resolved by Saturday morning at 11 am.

![image](https://github.com/kavismith/post-install-config/assets/143667203/ff11302a-c1d4-4ee4-a4df-7c12b10d1c7e)

Create a new SLA named "SEV-B" with a 4-hour grace period and a 24/7 schedule. This means that if a ticket is received on a Sunday at 3 pm, it should be completed by 7 pm on that same Sunday.

![image](https://github.com/kavismith/post-install-config/assets/143667203/cba6043d-041f-4ad2-88eb-399299f0c4fc)

Lastly, establish the "SEV-C" SLA with an 8-hour grace period and a schedule aligned with normal business hours, Monday to Friday, from 8 am to 5 pm, including US holidays. If an issue arises on a Friday at 2 pm, you have until 2 pm on the following Monday to close the ticket.

By following these steps, you will have created three distinct SLAs (SEV-A, SEV-B, and SEV-C) that outline specific timeframes for ticket resolution based on different criteria, ensuring efficient and consistent handling of support requests.
</p>
<p>

</p>
<br />

<h2>Create Help Topics</h2>

Lastly, in our administrative tasks, we will create Help Topics as an Admin. Help Topics serve as a critical factor in determining both the assignment of agents to tickets and the appropriate department responsible for handling specific issues.

![image](https://github.com/kavismith/post-install-config/assets/143667203/1e4a6fa1-0891-4cfc-a2ce-ec1dc6f4f60e)

Name the first Help Topic as "Busness Crital Outage."

![image](https://github.com/kavismith/post-install-config/assets/143667203/ad7d5c6a-4712-4119-8cb1-1c022550f994)

Name the second Help Topic as "Personal Computer Issues."

![image](https://github.com/kavismith/post-install-config/assets/143667203/f747d8b4-0f0e-4b9f-8a0d-b1e34e7d244b)

Designate the third Help Topic for "Equipment Request" requests.

![image](https://github.com/kavismith/post-install-config/assets/143667203/08b9d0c7-7e11-4af4-a51e-8358e0c88d7d)

Designate the fourth Help Topic for "Password Reset" requests.

![image](https://github.com/kavismith/post-install-config/assets/143667203/279d566d-c649-4e16-bb50-dc545da1187f)

</p>
<p>
</p>
<br />
