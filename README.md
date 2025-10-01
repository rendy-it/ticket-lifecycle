<p align="center">
<img width="2560" height="1440" alt="osTicket" src="https://github.com/user-attachments/assets/50906bf0-49c0-4637-bdd4-f6f7da339a42" />


</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Windows and Linux Virtual Machines on Microsoft Azure
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10 Pro </b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

-	Ticket Intake
-	Ticket Assignment and Communication
-	Working Tickets
-	Resolution of Tickets


<h2> << Ticket Intake >> </h2>
<p>
<img width="1151" height="651" alt="Step 1" src="https://github.com/user-attachments/assets/2dda1b78-e215-4220-9a4e-dc19521610ca" />


</p>
<p>
  
- Begin by going to the osTicket Support Center page: http://localhost/osTicket to create a ticket as an end user.
  -	Select “Open a New Ticket”.


</p>
<br />
<p>
<img width="842" height="990" alt="Step 1a" src="https://github.com/user-attachments/assets/26a13d30-5f61-4de1-abc5-28d3a10f58fd" />



<p>
  
- Recall in the previous project that we created 2 users. One of them was named “Karen” so we will input that user’s info.
- For the Help Topic we went with “Report a Problem”.
- For the Issue Summary, make it correspondent to whichever issue the person may have.
- Then select “Create Ticket”. 


  
</p>
<br />
<p>
<img width="963" height="407" alt="Step 1b" src="https://github.com/user-attachments/assets/93446a31-9cc7-430a-9f31-bf92e3cf258c" />


</p>
<p>
  
- Next, Click on the Admin Panel at the top right.


</p>
<br />
<p>
<img width="737" height="884" alt="Step 1b1" src="https://github.com/user-attachments/assets/19d6f19e-d9ae-4f32-8f7b-26932064e63e" />


</p>
<p>
  
- The Admin Panel is where you configure settings on the backend for osTicket.


</p>
<br />

<h2> << Setup 2: Configure Agent Roles >> </h2>

<p>
<img width="963" height="452" alt="Step 2" src="https://github.com/user-attachments/assets/b3b9875d-7a4f-4669-9be5-969458021d5d" />


</p>
<p>
  
- Once on the Admin Panel page, we are now going to create our osTicket role.
- We are going to create a Supreme Admin Role to give it lots of permissions. This is just an example as this is not normal in the work field.
- Go to the “Agents” tab. Select “Roles” then select “Add New Role”.




</p>
<br />
<p>
<img width="960" height="624" alt="Step 2a" src="https://github.com/user-attachments/assets/4c95b7a0-4fb0-40c4-af4e-21a47cba6dfc" />


<p>
  
- Next, input the name “Supreme Admin” then select “Permissions”.
   
</p>
<br />
<p>
<img width="964" height="761" alt="Step 2b" src="https://github.com/user-attachments/assets/add345fe-a9ba-495a-bd42-bc30f0524ae3" />


<p>
  
- Next, be sure to check every single permission for the “Tickets”, “Tasks” and “Knowledgebase” tabs then select “Add Role”.
   
</p>
<br />
<p>
<img width="963" height="501" alt="Step 2c" src="https://github.com/user-attachments/assets/1ef5f87c-3b52-478d-8da7-a20c80f9592b" />


<p>
  
- Now you have created your first Role as an Admin in osTicket.
   
</p>
<br />


<h2> << Setup 3: Configure Departments  >> </h2>
<p>
<img width="966" height="382" alt="Step 3" src="https://github.com/user-attachments/assets/df440bf5-544d-4634-8f1e-51e0f3924bb1" />

</p>
<p>
  
- We are going to create a department in osTicket.
- On the Admin Panel page, go to the "Agents" tab. 
- Select “Departments” then select “Add New Department”.


</p>
<br />

<p>
<img width="962" height="1168" alt="Step 3a" src="https://github.com/user-attachments/assets/2b44c302-cb77-4b8a-bf5f-f88534a7085a" />

</p>
<p>
  
- Next, input the name “SysAdmins” then select “Create Dept”.


</p>
<br />

<p>
<img width="963" height="435" alt="Step 3b" src="https://github.com/user-attachments/assets/fd33de3f-89ef-4065-94c5-d77891667511" />


</p>
<p>
  
- Now you have created your first Department in osTicket. 


</p>
<br />

<h2> << Setup 4: Configure Teams  >> </h2>
<p>
<img width="963" height="365" alt="Step 4" src="https://github.com/user-attachments/assets/35c01c0e-86bf-40c6-a774-80f68269910b" />

</p>
<p>
  
-	We are going to create a Team in osTicket.
-	On the Admin Panel page, go to the "Agents" tab.
-	Select “Teams” then select “Add New Team”.


</p>
<br />

<p>
<img width="964" height="731" alt="Step 4a" src="https://github.com/user-attachments/assets/8d9bea70-b2be-404c-b5f9-1c501e343660" />


</p>
<p>
  
- Next, input the name "Online Banking" then select “Create Team”.


</p>
<br />

<p>
<img width="963" height="387" alt="Step 4b" src="https://github.com/user-attachments/assets/e888620f-b21c-48de-9cfb-1009afeb6508" />


</p>
<p>
  
- Go back to the Teams page and you will see your new team created.


</p>
<br />

<h2> << Setup 5: Allow anyone to set up tickets >> </h2>
<p>
<img width="962" height="737" alt="Step 5" src="https://github.com/user-attachments/assets/b94a56d6-4b45-4d3d-bd5b-7b38f9f1419f" />


</p>
<p>
  
- We are going to turn off the setting that requires registration and login for a user to create tickets.
- On the Admin Panel page, go to the "Settings" tab.
- Select “Users” and make sure that the “Require registration and log in to create tickets” box is checked off then select “Save Changes”.


</p>
<br />


<h2> << Conclusion >> </h2>

<p>
  
- Close the Remote Desktop connection.
- Go Back to your Azure resource group page.
- Make sure your VMs are on “Stop” status if you are not going to use them right away. This way you will not be charged while they are not in use.
- Also, make sure your VMs are on “Stop” status if you are not going to use them right away. This way you will not be charged while they are not in use.
- To conclude, we have successfully configured osTicket inside our Windows Virtual Machine that is being resourced by the Azure cloud infrastructure. 


</p>
<br />

