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
-	Ticket Assignment and Communication | Working Tickets |	Resolution of Tickets
  

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
<img width="842" height="991" alt="Step 1b" src="https://github.com/user-attachments/assets/cd19122c-31ba-4917-aa20-0c0f36349080" />


</p>
<p>
  
- Next, we are going to create another ticket but this time for the other user that we created named “Ken”.
- Open a New Ticket again.
- Recall in the previous project that we created 2 users. One of them was named “Ken” so we will input that user’s info.
- For the Help Topic we went with “Report a Problem/Password Reset”.
- For the Issue Summary it, make it correspondent to whichever issue the person may have.
- Then select “Create Ticket”. 


</p>
<br />

<h2> << Ticket Assignment and Communication | Working Tickets |	Resolution of Tickets >> </h2>

<p>
<img width="600" height="494" alt="Step 2" src="https://github.com/user-attachments/assets/5ae610c2-ed55-4ef3-ac65-d6ed8f2678fe" />


</p>
<p>
  
- Go to the osTicket login page: http://localhost/osTicket/scp/login.php .
	- Log in as the admin user we created in the previous project.
	- One of mine was Jane.


</p>
<br />
<p>
<img width="962" height="462" alt="Step 2a" src="https://github.com/user-attachments/assets/766068ee-fba6-48c4-959c-8ef26ec036e4" />


<p>
  
- Once logged in, you will see the 2 tickets that were submitted by the users Karen and Ken. Select the “Online Banking” one from Karen.
   
</p>
<br />
<p>
<img width="770" height="999" alt="Step 2a1" src="https://github.com/user-attachments/assets/bb8d20f5-e701-4eab-97af-50949772acb9" />


<p>
  
- As a Help Desk Agent (Jane) will observe the ticket’s properties.
- The Priority, Department, SLA and who the ticket is assigned to.
- Set the Ticket’s properties by selecting the SLA Plan “Default SLA”.

   
</p>
<br />
<p>
<img width="650" height="255" alt="Step 2a2" src="https://github.com/user-attachments/assets/9ac077ff-1a0d-44a6-a643-2fbbc5aa6df7" />


<p>
  
- Change it to “SEV-A” and write down a reason. Then select “Update”.
   
</p>
<br />

<p>
<img width="650" height="255" alt="Step 2a3" src="https://github.com/user-attachments/assets/29292c16-94e2-45da-8a78-eb594626a093" />


<p>
  
- Then select the Help Topic “Report a Problem”.
- Change it to “Report a Problem / Business Critical Outage” and write down the reason. Then select “Update”.

   
</p>
<br />

<p>
<img width="650" height="255" alt="Step 2a4" src="https://github.com/user-attachments/assets/fc90d09e-9485-4a8a-80d3-0af96de7d328" />


<p>
  
- Then Select the Assigned To “Unassigned”.
- Change it to “Online Banking” and write down a reason. Then Select “Assign”.

   
</p>
<br />

<p>
<img width="889" height="997" alt="Step 2a5" src="https://github.com/user-attachments/assets/b1ec1c08-6142-4a93-9d6b-31a2276e007b" />


<p>
  
- So, I assigned the ticket to the Online Banking Team and made it so that Jane took over the ticket. I acknowledged the issue to Karen the user and responded with an update of what the problem could be related to after investigating. This assures Karen that I am working on the problem. Then I updated Karen on what was done to solve the problem, assuring her that everything is back up and running.
- The Ticket Thread section is there to give the agent access to communicate to the customer, to keep them updated on the ticket’s progress of being resolved. It’s also very important through good communication skills to remain polite and empathetic with the customers.

   
</p>
<br />

<p>
<img width="770" height="998" alt="Step 2a6" src="https://github.com/user-attachments/assets/b3030823-313f-49b3-9124-724f4ab4e321" />


<p>
  
- Now that everything is resolved, you can now close the ticket. Select the Status “Open” and select “Resolved”. Then select “Close”.
   
</p>
<br />

<p>
<img width="650" height="255" alt="Step 2b1" src="https://github.com/user-attachments/assets/496fa44d-37df-4676-ab7e-1d25bb4f6727" />


<p>
  
- Next, we are going to assign the other ticket to John since John has a support role.
- Jane as the Admin Agent will give John the assignment. Select the other ticket that was submitted by Ken from the previous steps above.
- This ticket submitted by Ken is a Password Reset issue and we are going to let John from the Support Team take over.
  
   
</p>
<br />

<p>
<img width="605" height="546" alt="Step 2b2" src="https://github.com/user-attachments/assets/7e7a37c2-2ff9-4653-abc0-a420b4445884" />


<p>
  
- Next, log out and go log in as John.
   
</p>
<br />

<p>
<img width="960" height="464" alt="Step 2b2a" src="https://github.com/user-attachments/assets/2ec5c67a-cd35-45fc-9ffa-d1bbc79f4bdc" />


<p>
  
- Then select the ticket assigned which in this case is the Password Reset ticket.

   
</p>
<br />

<p>
<img width="897" height="996" alt="Step 2b3" src="https://github.com/user-attachments/assets/4b4e08f8-b454-419e-b461-bcc1a6881d66" />


<p>
  
- The issue has been resolved as we can see by reading the Ticket Thread log.

   
</p>
<br />

<p>
<img width="822" height="994" alt="Step 2b4" src="https://github.com/user-attachments/assets/ed4d3e5a-6b7b-4c63-8af3-51a2155c40f6" />


<p>
  
- You can now close the ticket to status resolved. 

   
</p>
<br />

<p>
<img width="960" height="441" alt="Step 2c" src="https://github.com/user-attachments/assets/92992a73-73f1-435c-8ccf-381720964d29" />


<p>
  
- All tickets have been resolved.

   
</p>
<br />

<h2> << Conclusion >> </h2>

<p>
  
- Close the Remote Desktop connection.
- Go Back to your Azure resource group page.
- Make sure your VMs are on “Stop” status if you are not going to use them right away. This way you will not be charged while they are not in use.
- Also, make sure your VMs are on “Stop” status if you are not going to use them right away. This way you will not be charged while they are not in use.
- To conclude, we were able to create tickets from an end user’s perspective. Then we were able to go and solve those tickets through the Helpdesk Agents perspective. Both from an admin role and a support role. 


</p>
<br />

