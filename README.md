


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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
![image](https://github.com/kavismith/post-install-config/assets/143667203/37246ada-bb18-4d8d-9699-ebf28abaaed8)

</p>
<p>
Create a Role called "supreme Admin". This will allow someone to create tickets, delete tickets and even assign task to agents or teams. To do so, click on Admin Panel, Agents, and then Roles. Then you want to select add a new role, name the role "Supreme Admin", and then assign permissions for the role. Select all that will apply to the admin role as far as the permissions sucha s permissions to work on tickets and tasks. 
</p>
<br />

<p>![image](https://github.com/kavismith/post-install-config/assets/143667203/2966b4e4-44c4-4259-afc0-b2eda79819b3)

</p>
<p>Now configure some Departments. Tickets are assigmed by departments, so if a cus0tomer or team member is having a problem with Networking, then a ticket will be assigned to the networking department or if they need help with Maintenance then the tipcket will be asigned to the Maintenance Department. Some departments can be archived, which will disabled tickets to no longer be transferred. To craete a new department, you want to select Admin Panel, Agents, and  then Departments. Select new department,name teh department" System Administrators" for this examples. Keep all the defalt setting for this practice. But you can go in and assign a manager, SLA's make the department private or publicand even change the outgoing mail settings. 
</p>
<br />

<p>
![image](https://github.com/kavismith/post-install-config/assets/143667203/5d57214c-2070-42a8-9320-b50e57f2938a)
![image](https://github.com/kavismith/post-install-config/assets/143667203/b3c4c8a9-2cf6-47b7-a886-7fcdaa0ba7b7)

</p>
<p>
Teams allows you to be able to pull agents from different departments to handle certain tickets or a  specific issue. You can also assign a team lead to recieve notification for the team. To access teams and create a new team, go to Admin Panel, Agents, and then se;ect new team. Name the team Level ii support and select the  members you want on the team
</p>
<br />

<h2>Configuration Steps</h2>

<p>
![image](https://github.com/kavismith/post-install-config/assets/143667203/e438523e-95c6-4638-800f-a3f1b4a91cf4)


</p>
<p>
Now, allow anyone to create tickets. To do so you need to select the Admin Panel, Settings, then select User settings amnd make sure required registration and login to create tickets is unchecked.

</p>
<br />

<p>
![image](https://github.com/kavismith/post-install-config/assets/143667203/49789ff9-b98e-480c-a32d-6650ceffbf93)

![image](https://github.com/kavismith/post-install-config/assets/143667203/8bb78118-34c2-4b89-a349-5fa869c52892)
![image](https://github.com/kavismith/post-install-config/assets/143667203/ec0c50b9-86a5-45e0-b8c8-0ac40cf46452)
![image](https://github.com/kavismith/post-install-config/assets/143667203/a476d19c-9de7-4837-aba3-cba565d295e7)
![image](https://github.com/kavismith/post-install-config/assets/143667203/1ef46656-8999-44b2-97b9-913ea0810399)
![image](https://github.com/kavismith/post-install-config/assets/143667203/4fa26003-a442-4cd0-862d-9bbc08d425b9)
![image](https://github.com/kavismith/post-install-config/assets/143667203/d2acc3f6-cc8e-4b7d-b017-cf95befb0bc6)

</p>
<p>
Agents are assigned to work tickets by reponing and solving them. Agents are also assigned to different departments and have a certain role assigned to them. Admins can even reset agents passwords. To add a new Agent you need to go to Admin Panel, Agents and select Add new. Name the first Agent Jane Carter, email is jane.carter@osticket.com, and the apply a username jane.carter. Also, assign Jane Carter to the primary department as Maintenance and give her all access as well. Create another Agent name John Smith, email john.smith@osticket.com, and username john.smith. Mae sure give John Smith asscess to Supreme Administrator and the role as Supreme admin
</p>
<br />

<p>
![image](https://github.com/kavismith/post-install-config/assets/143667203/5d57214c-2070-42a8-9320-b50e57f2938a)
![image](https://github.com/kavismith/post-install-config/assets/143667203/b3c4c8a9-2cf6-47b7-a886-7fcdaa0ba7b7)

</p>
<p>
Teams allows you to be able to pull agents from different departments to handle certain tickets or a  specific issue. You can also assign a team lead to recieve notification for the team. To access teams and create a new team, go to Admin Panel, Agents, and then se;ect new team. Name the team Level ii support and select the  members you want on the team
</p>
<br />
