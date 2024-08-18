<h1>Connecting users to their assigned devices</h1>

<h2>Description</h2>
In this lab, you’re working as a security analyst and you’re responsible for developing an algorithm that connects users to their assigned devices. You’ll write code that indicates if a user is approved
on the system and has brought their assigned device to the security team.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Environments Used </h2>

- <b>Python Notebook</b> 

<h2>Program walk-through:</h2>

<p align="center">
Indices: First, to explore how indices in lists work, run the following code cell as is and observe the output.Then, replace each 0 with another index and run the cell to observe what happens <br/>
<img src="https://imgur.com/LoqfvNw.png" height="80%" width="80%" alt="Assigning Steps"/>
<br />
Append:There’s a new employee joining the organization, and they need to be provided with a username and device ID. In the following code cell, you are given a username and device ID of this new user,
stored in the variables new_user and new_device, respectively. Use the .append() method to add these variables to the approved_users and approved_devices respectively. Afterwards, display the approved_users and approved_devices variables to confirm the added information.  <br/>
<img src="https://imgur.com/2nG7SMA.png" height="80%" width="80%" alt="Assigning Steps"/>
<br />
Remove:An employee has left the team and should no longer have access to the system. In the following code cell, you are given the username and device ID of the user to be removed, stored in the variables
removed_user and removed_device respectively. Use the .remove() method to remove each of these elements from the corresponding list. Afterwards, display both the approved_users and the approved_devices variables to view the removed users. Run the code and observe the results. <br/>
<img src="https://imgur.com/ru3LIDU.png" height="80%" width="80%" alt="Assigning Steps"/>
<br />
Confirming: As part of verifying a user’s identity in the system, you’ll need to check if the user is one of the approved users. Write a conditional statement that verifies if a given username is an element of
the list of approved usernames. If it is, display "The user ______ is approved to access the system.". Otherwise, display "The user ______ is not approved to access the system.".  <br/>
<img src="https://imgur.com/sqNBRxO.png" height="80%" width="80%" alt="Assigning Steps"/>
<br />
Index: Add a statement to display ind in the following code cell to explore the value it contains.  <br/>
<img src="https://imgur.com/jBIWISf.png" height="80%" width="80%" alt="Assigning Steps"/>
<br />
Storing: First, use the .index() method again to find the index of username in the approved_users and store that in a variable named ind. Then, connect ind to the approved_devices and display the device ID located at the index ind. Afterwards, run the cell to observe the result.  <br/>
<img src="https://imgur.com/JZToVOu.png" height="80%" width="80%" alt="Assigning Steps"/>
<br />
Approval: Your next step in creating the algorithm is to determine if a username and device ID correspond.To do this, write a conditional that checks if the username is an element of the approved_devices
and if the device_id stored at the same index as username matches the device_id entered. You’ll use the logical operator and to connect the two conditions. When both conditions evaluate to True, display a message that the username is approved and another message that the user has their assigned device.  <br/>
<img src="https://imgur.com/qZnX1AU.png" height="80%" width="80%" alt="Assigning Steps"/>
<br/>
Deny: It would also be helpful for users to receive messages when their username is not approved or their device ID is incorrect. Add to the code by writing an elif statement. This elif statement should run when the username is part of the approved_users but the device_id doesn’t match the corresponding device ID in the approved_devices. The statement should also display two messages conveying that information. <br/>
<img src="https://imgur.com/uIveBT3.png" height="80%" width="80%" alt="Assigning Steps"/>
<br/>
Automate: In this task, you’ll complete your algorithm by developing a function that uses some of the code you’ve written in earlier tasks. This will automate the login process.Must define a function named login that takes in two parameters, username and device_id. Afterwards, call the function and pass in different username and device ID combinations to experiment and observe the function’s behavior. <br/>
<img src="https://imgur.com/2bYKAt0.png" height="80%" width="80%" alt="Assigning Steps"/>
<img src="https://imgur.com/EMKdD77.png" height="80%" width="80%" alt="Assigning Steps"/>
<br/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
