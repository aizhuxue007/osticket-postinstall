<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Post-Installation: Setting up a Helpdesk Environment</h1>
This tutorial guides the configuration of Roles, Departments, Teams, Agents, Users, SLA and Help Topics to simulate on-the-job ticketing system experience.<br/>

<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (2 vCPUs)

<h2>Documentation</h2>

- ### [osTicket 1.15.8](https://docs.osticket.com/en/v1.15.8/)

<h2>Post-installation and Configuration Steps</h2>

<p>
  1. Set up <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">Roles</a> <br>
- Admin Panel > Agents > Roles <br>
- Name new Role as: Super Admin (Whatever you like)
- Check all permission boxes
</p>
<p><img width="1486" alt="Screenshot 2023-01-21 at 11 28 09 AM" src="https://user-images.githubusercontent.com/17282458/213876776-8b974304-de5e-4ca5-bf87-50a62969bb23.png">
<img width="1220" alt="Screenshot 2023-01-21 at 11 28 56 AM" src="https://user-images.githubusercontent.com/17282458/213876782-4066f00a-f192-472b-89cb-86116e8297c2.png">
<img width="1083" alt="Screenshot 2023-01-21 at 11 29 33 AM" src="https://user-images.githubusercontent.com/17282458/213876783-f9d0fd27-ee3e-4f27-a71c-c52aa0c4140a.png">
<img width="1257" alt="Screenshot 2023-01-21 at 11 30 07 AM" src="https://user-images.githubusercontent.com/17282458/213876791-dfebd57a-df41-4798-a643-ff6a7de8efb0.png">


</p>
<br />

<p>  
  2. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Agents/Departments.html">Departments</a> <br>
- Admin Panel > Agents > Departments <br>
- Name new Department as: System Administrators
</p>
<p><img width="1787" alt="postinstall2-1" src="https://user-images.githubusercontent.com/17282458/213877049-f1f5f658-195c-45a4-9783-7b413c2d1397.png">

<img width="1277" alt="Screenshot 2023-01-21 at 11 35 42 AM" src="https://user-images.githubusercontent.com/17282458/213877059-bef10d58-8b7f-4168-a779-76fe2f8165a4.png">

</p>
<br />

<p>
3. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Agents/Teams.html">Teams</a><br>
- Admin Panel > Agents > Teams <br>
- Add 2 new Teams: <br>
&emsp;- Level I Support <br>
&emsp;- Level II Support <br>
</p>
<p>
<img width="1565" alt="post-install3-1" src="https://user-images.githubusercontent.com/17282458/213877188-bbdf7350-1dfc-433b-9259-196316235c4d.png">
<img width="1542" alt="postinstall3-2" src="https://user-images.githubusercontent.com/17282458/213877205-9f3b7985-2a24-4568-a8a8-a362d84bcea4.png">
<img width="1468" alt="postinstall3-3" src="https://user-images.githubusercontent.com/17282458/213877222-0e1db988-dc6f-422b-b578-27eb9115b75a.png">

</p>
<br />


<p>
4. Allow registered users to create tickets <br>
- Admin Panel > Settings > User Settings <br>
- Select Registration Required: Require registration and login to create tickets 
</p>
<p>
<img width="1647" alt="postinstall4-1" src="https://user-images.githubusercontent.com/17282458/213877321-50e34748-578a-4419-891d-97be7a5e9c8a.png">
</p>
<br />


<p>
5. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Agents/Agents.html">Agents</a> <br>
- Admin Panel > Agents > Add New<br>
- Add 2 New Agents: <br>
&emsp;- Janette<br>
&emsp;- Jim
- Make sure to assign access to these two!
</p>
<p>
<img width="1575" alt="Screenshot 2023-01-21 at 11 43 09 AM" src="https://user-images.githubusercontent.com/17282458/213877514-c0e9213b-2b69-4a85-ab6d-9175e5011022.png">
<img width="1733" alt="Screenshot 2023-01-21 at 11 44 03 AM" src="https://user-images.githubusercontent.com/17282458/213877516-3eb0b930-28a7-4881-a095-5c836bce8ddb.png">
<img width="1532" alt="Screenshot 2023-01-21 at 11 44 19 AM" src="https://user-images.githubusercontent.com/17282458/213877518-52706810-f079-4199-b547-50f02d1ffeaa.png">
<img width="1245" alt="Screenshot 2023-01-21 at 11 46 04 AM" src="https://user-images.githubusercontent.com/17282458/213877520-d38e5aa6-b0b1-41ad-a451-986150474d5f.png">

</p>
<br />



<p>
6. Set up <a href="https://docs.osticket.com/en/v1.15.8/Agent/Users/User%20Directory.html">Users</a> <br>
- Think of Users as customers <br>
- Agent Panel > Users > Add New <br>
- Add 2 new Users: <br>
&emsp;- Peter Schiff <br>
&emsp;- Loida Schiff
<p>
<img width="1677" alt="Screenshot 2023-01-21 at 11 52 32 AM" src="https://user-images.githubusercontent.com/17282458/213877898-2a98d105-3dc3-4386-9c02-fc2e330b5b55.png">
<img width="1448" alt="Screenshot 2023-01-21 at 11 53 25 AM" src="https://user-images.githubusercontent.com/17282458/213877902-d3b6e133-9415-437c-bdf8-0875d7838b1b.png">
<img width="1399" alt="Screenshot 2023-01-21 at 11 54 56 AM" src="https://user-images.githubusercontent.com/17282458/213877904-20134e94-aff2-4aed-9137-bece34bfe6c3.png">

</p>
</p>
<br />


<p>
7. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Manage/SLA%20Plans.html?highlight=sla">SLA (Service Level Agreements)</a> <br>
- Admin Panel > Manage > SLA <br>
- add 3 SLAs <br>
&emsp;- Sev-A (1 hour, 24/7) <br>
&emsp;- Sev-B (4 hours, 24/7) <br>
&emsp;- Sev-C (8 hours, business hours)
</p>
<p><img width="1683" alt="Screenshot 2023-01-21 at 11 57 31 AM" src="https://user-images.githubusercontent.com/17282458/213878312-e5c28184-5f60-4c2c-9668-0320c7ddeb98.png">
<img width="1236" alt="Screenshot 2023-01-21 at 11 59 09 AM" src="https://user-images.githubusercontent.com/17282458/213878315-9671c674-82d9-4283-a5f4-660b9e2fbf79.png">
<img width="1181" alt="Screenshot 2023-01-21 at 12 00 14 PM" src="https://user-images.githubusercontent.com/17282458/213878333-03989e4d-ff25-402b-a665-7fa23f0d1ac5.png">

</p>
<br />


<p>
8. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Manage/Help%20Topic.html">Help Topics</a> <br>
- Admin Panel > Manage > Help Topics <br>
- Add 4 new Help Topics: <br>
&emsp;- Business Critical Outage <br>
&emsp;- Personal Computer Issues <br>
&emsp;- Equipment Request <br>
&emsp;- Password Reset <br>
</p>
<p>
<img width="1276" alt="Screenshot 2023-01-21 at 12 06 26 PM" src="https://user-images.githubusercontent.com/17282458/213878579-68f6d36e-f643-44e3-a753-8ee93e0be4b8.png">
<img width="1131" alt="Screenshot 2023-01-21 at 12 11 21 PM" src="https://user-images.githubusercontent.com/17282458/213878583-f4b7807c-1c7c-4f2c-941c-200a73fdf251.png">

</p>
<br />

Now that everything is all set up, let's create tickets and resolve them!
<a href="https://github.com/aizhuxue007/osticket-lifecycle">Go to Ticket Lifecycle</a>
