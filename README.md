<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Setting up a Helpdesk Environment</h1>
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
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>  
  2. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Agents/Departments.html">Departments</a> <br>
- Admin Panel > Agents > Departments <br>
- Name new Department as: System Administrators
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
4. Allow registered users to create tickets <br>
- Admin Panel > Settings > User Settings <br>
- Select Registration Required: Require registration and login to create tickets 
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />


<p>
5. Set up <a href="https://docs.osticket.com/en/v1.15.8/Admin/Agents/Agents.html">Agents</a> <br>
- Admin Panel > Agents > Add New<br>
- Add 2 New Agents: <br>
&emsp;-Janette<br>
&emsp;-Jim
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />



<p>
6. Set up <a href="https://docs.osticket.com/en/v1.15.8/Agent/Users/User%20Directory.html">Users</a> <br>
- Think of Users as customers <br>
- Agent Panel > Users > Add New <br>
- Add 2 new Users: <br>
&emsp;- Peter <br>
&emsp;- Barbara
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

Now that everything is all set up, let's create tickets and resolve them!
<a href="https://github.com/aizhuxue007/osticket-lifecycle">Go to Ticket Lifecycle</a>
