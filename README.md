<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>
This lab demonstrates the necessary changes I make to configure osTicket so it can be used as a proper ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b>


<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/df4cff58-3e80-42ea-ba63-6dbdc78f1d28)

![image](https://github.com/user-attachments/assets/5f597768-5cc4-49bc-a220-a0e10adf6c72)

<p>
After installing osTicket, it is now time to make configurations to use it as a ticketing system. One thing to note is that I switch between Admin and Agent panels as each panel has different configurations. To tell which panel is used, look at the top right of the osTicket screen. If it reads Agent Panel, the Admin panel is the one being used and vice versa.

The first step to take is to make a new role called Supreme Admin. For the purposes of this lab, I am intentionally creating a role that has every permission that can be granted. To create a new role, open the Admin panel enter the Agents Menu. Click on Roles and create the new role from there.
</p>
<br />

![image](https://github.com/user-attachments/assets/c67bd41b-ebfd-4675-a138-fb34ee209f50)

<p>
Next, a new Department will be created for System Administrators. In the Admin panel, open the Agents menu and click on Departments to create a new Department within osTicket.
</p>
<br />

![image](https://github.com/user-attachments/assets/e5b52bab-c7e2-49a9-9bca-73a757cd85bc)

<p>
A new Level II Support Team will have to be created to supplement the Level I Support Team already made within osTicket. To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add any new teams that need to be created.
</p>
<br />

![image](https://github.com/user-attachments/assets/d629cb30-cce3-466d-a850-22ad1252a5a2)

![image](https://github.com/user-attachments/assets/27d1d015-5e8e-4b25-bcbe-0630faad6650)

<p>
New agents will have to be created so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent. In this case, Jane and John Doe are created.
</p>
<br />

![image](https://github.com/user-attachments/assets/8ca1f29b-d23c-48d2-bf5c-863d7f23507e)

<p>
New users will be created so they can create tickets so that the agents can receive and triage them. To create new users, enter the Agents panel and open the Users menu. Click on Add User and create the account credentials necessary for each new user. In this case, Karen and Ken have been created.
</p>
<br />

![image](https://github.com/user-attachments/assets/c6a3563f-bafe-44b1-8282-73e8dde1130e)

<p>
Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact. To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively.
</p>
<br />

![image](https://github.com/user-attachments/assets/990f2385-be5b-4406-ac87-874ca44d37a7)

<p>
Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, I have added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.
</p>
<br />

<h2>osTicket Configurations are Complete </h2>

Now that the configurations have been set in place, I can now utilize osTicket as a proper ticketing system. I can create tickets and be able to traige them as if I were in a real environment.
