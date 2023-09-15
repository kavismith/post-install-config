


<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. We will be working as an Admin, who sets up the ticketing system and defines the roles and other administrator duties.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Roles
- Create DEpartments
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
Create a Role called "supreme Admin". This will allow someone to create tickets, delete tickets and even assign task to agents or teams. To do so, click on Admin Panel, Agents, and then Roles. Then you want to select add a new role, name the role "Supreme Admin", and then assign permissions for the role. Select all that will apply to the admin role as far as the permissions sucha s permissions to work on tickets and tasks. 
</p>
<br />

<h2>Create Departments</h2>

![image](https://github.com/kavismith/post-install-config/assets/143667203/55c1db44-a4a0-496a-a724-a03ed91f60a2)

![image](https://github.com/kavismith/post-install-config/assets/143667203/7c6a3d83-39e5-4d40-873b-c74590609f72)


</p>
<p>Now configure some Departments. Tickets are assigmed by departments, so if a customer or team member is having a problem with networking, then a ticket will be assigned to the networking department or if they need help with Maintenance then the ticket will be asigned to the Maintenance Department. Some departments can be archived, which will disabled tickets to no longer be transferable. To create a new department, you want to select Admin Panel, Agents, and  then Departments. Select new department,name the department" System Administrators" for this examples. Keep all the default setting for this practice. You can go in and assign a manager, SLA's make the department private or publicand even change the outgoing mail settings. 
</p>
<br />

<h2>Create Teams</h2>

![image](https://github.com/kavismith/post-install-config/assets/143667203/5d57214c-2070-42a8-9320-b50e57f2938a)
![image](https://github.com/kavismith/post-install-config/assets/143667203/b3c4c8a9-2cf6-47b7-a886-7fcdaa0ba7b7)

</p>
<p>
Teams allows you to be able to pull agents from different departments to handle certain tickets or a  specific issue. You can also assign a team lead to recieve notification for the team. To access teams and create a new team, go to Admin Panel, Agents, and then select new team. Name the team Level ii support and select the  members you want on the team
</p>
<br />

<h2>Allow Any One To Create Tickets</h2>


![image](https://github.com/kavismith/post-install-config/assets/143667203/e438523e-95c6-4638-800f-a3f1b4a91cf4)


</p>
<p>
Now, allow anyone to create tickets. To do so you need to select the Admin Panel, Settings, then select User settings amnd make sure required registration and login to create tickets is unchecked.

</p>
<br />

<h2>Create Agents</h2>
  
![image](https://github.com/kavismith/post-install-config/assets/143667203/49789ff9-b98e-480c-a32d-6650ceffbf93)

![image](https://github.com/kavismith/post-install-config/assets/143667203/8bb78118-34c2-4b89-a349-5fa869c52892)

![image](https://github.com/kavismith/post-install-config/assets/143667203/d2acc3f6-cc8e-4b7d-b017-cf95befb0bc6)

![image](https://github.com/kavismith/post-install-config/assets/143667203/1ef46656-8999-44b2-97b9-913ea0810399)

![image](https://github.com/kavismith/post-install-config/assets/143667203/4fa26003-a442-4cd0-862d-9bbc08d425b9)

![image](https://github.com/kavismith/post-install-config/assets/143667203/a476d19c-9de7-4837-aba3-cba565d295e7)

</p>
<p>
Agents are assigned to work tickets by reponing and solving them. Agents are also assigned to different departments and have a certain role assigned to them. Admins can even reset agents passwords. To add a new Agent you need to go to Admin Panel, Agents and select Add new. Name the first Agent Jane Carter, email is jane.carter@osticket.com, and the apply a username jane.carter. Also, assign Jane Carter to the primary department as Maintenance and give her all access as well. Create another Agent name John Smith, email john.smith@osticket.com, and username john.smith. Mae sure give John Smith asscess to Supreme Administrator and the role as Supreme admin
</p>
<br />

<h2>Create Users</h2>

![image](https://github.com/kavismith/post-install-config/assets/143667203/2b230105-3130-4c01-9cdf-cd8142d6faff)

![image](https://github.com/kavismith/post-install-config/assets/143667203/5b9e4b78-ba2d-48b8-afb1-7a31f9bbbeb2)


![image](https://github.com/kavismith/post-install-config/assets/143667203/38064188-15af-455f-9930-672407491a33)

![image](https://github.com/kavismith/post-install-config/assets/143667203/7494b2f8-1b29-4f0d-bc5c-6dfb8e024581)


</p>
<p>
Users are allowed to creat accounts to sign in and create tickets. When you access the User Directory , it allows agents to search for tickets by the users.Users can also be added for deleted from the User directory section in the Agent Panel. To locate the User Directory, click in Agent Panel, then select users and then click on add new users. 
</p>
<br />


<h2>Create SLA's</h2>


![image](https://github.com/kavismith/post-install-config/assets/143667203/888520cd-05a6-4008-9e7e-c5cefeab843b)
![image](https://github.com/kavismith/post-install-config/assets/143667203/ff11302a-c1d4-4ee4-a4df-7c12b10d1c7e)
![image](https://github.com/kavismith/post-install-config/assets/143667203/cba6043d-041f-4ad2-88eb-399299f0c4fc)



</p>
<p>
Now, create an SLA(Service Level Agreement) which provides a certain time fram that a Help Desk Administrator expects tickets to be closed. To create SLAs you need to click on the Admin Panel, select manage, and then click on SLA and then add new SLA Plan. Name the first SLA SEV-A, the schedue 24/7 which means is a SEV-A comes on a Saturday at 10am it needs to resolved Saturday morninng at 11am. Creat a new SLA named SEV-B, with a 4 hour grace period and 24/7 schedule. So, if a ticket comes in on Sunday at 3pm then it needs to be completed by 7pm on sunday. Last we will create SEV-C SLA with a grace period of 8 hours witha  schedule of normal business hours Monday to Friday 8am-5pm including US Holidays. If anythinng happens on a Friday at 2pm, you have until 2pm on monday to close the ticket. 
</p>
<br />

<h2>Create Help Topics</h2>


![image](https://github.com/kavismith/post-install-config/assets/143667203/1e4a6fa1-0891-4cfc-a2ce-ec1dc6f4f60e)
![image](https://github.com/kavismith/post-install-config/assets/143667203/ad7d5c6a-4712-4119-8cb1-1c022550f994)
![image](https://github.com/kavismith/post-install-config/assets/143667203/f747d8b4-0f0e-4b9f-8a0d-b1e34e7d244b)
![image](https://github.com/kavismith/post-install-config/assets/143667203/08b9d0c7-7e11-4af4-a51e-8358e0c88d7d)
![image](https://github.com/kavismith/post-install-config/assets/143667203/279d566d-c649-4e16-bb50-dc545da1187f)



</p>
<p>
Last, we will be creating Help Topics as an Admin. Help Topics detwermines what agents will be assigned to the ticket as well as the type of department
</p>
<br />
