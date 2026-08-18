<h1>MS365 Admin Homelab</h1>


<h2>Description</h2>
A hands on project was completed using a Microsoft 365 homelab environment to practice core service desk tasks within the admin centre. Theses tasks will commonlly be seen in a typical user lifecycle from onboarding to offboarding.
<br />



<h2>Software Used </h2>

- Oracle VirtualBox
- Microsoft 365 admin center
- Microsoft Entra admin center


<h2>Walkthrough:</h2>

<p align="center">
Onboarding a new user<br/>
<p align="left">
Onboarding is the complete process of setting up a new starter, which includes creating the user account, assigning licences, and ensuring equipment works. For account setup this can be done in both the 365 center and the Entra Center. Entra has a many of the same features but with a focus on Users and Identities.


<p align="center">
Entra Tenant<br/>
<img src="https://github.com/user-attachments/assets/396e905a-3ea8-46db-8903-fe9577387374" height="80%" width="80%"/>
<p align="center">
Entra Homepage<br/>
 
<img src="https://github.com/user-attachments/assets/31a2670e-829f-4fb0-a195-891de7a80e36" height="80%" width="80%"/>

<p align="center">
Admin Center Homepage<br/>
<img src="https://github.com/user-attachments/assets/f5c7d6e8-cc8d-4fc4-b0ca-e3e371646e3d" height="80%" width="80%"/>

<p align="center">
New User Creation<br/>
 
<img src="https://github.com/user-attachments/assets/f80b6c65-975d-406b-b4d6-918350137f36" height="80%" width="80%"/>

Here I create a user named steve and can assign the relevant licences to the user. Location is also important to condsider due to data sovereignty laws.

<p align="center">
Role Based Access Control<br/>
<p align="left">
Understanding Role Based Access Control is important as it governs what a user can actually do once logged in. The analyst needs to know which roles correspond to which job functions to assign the correct permissions. This prevents a user from having too much or too little access. This can be done in Entra by navigating to the assigned roles of a user. In this example, Steve will manage SharePoint so I assigned the Sharepoint Admin role to the user.
<img src="https://github.com/user-attachments/assets/7fe19274-2389-4850-9e37-d2c0351e76e6" height="80%" width="80%"/>
<img src="https://github.com/user-attachments/assets/9e59164d-0a70-4f8d-8e18-8488c5a41a49" height="80%" width="80%"/>

<p align="center">
Password Reset Request<br/>
<p align="left">
Admins can reset their own passwords, but a common request an end user will make is for a password reset. Once verifying the request, it is as simple as navigating to a key icon by the users name in 365 admin center. In this example I reset a password for user Lara Croft.

<img src="https://github.com/user-attachments/assets/fdd02c18-bd5a-4675-a463-f6540eb3b1a1" height="80%" width="80%"/>

A temporary password can be auto created, or I can create my own. This may be a better option if I am direct communication with the user and can use an easily memorable phrase to login to their account, then be prompted to reset their password once access has been regained.

<img src="https://github.com/user-attachments/assets/da50adad-d40c-48f7-b366-ec2d29d510cc" height="80%" width="80%"/>


<p align="center">
Offboarding steps<br/>

<p align="left">
 
Offboarding is just as critical as onboarding because it secures the business when someone leaves. It is vital to prevent unauthorised access and ensure that company data remains protected after an employee's departure. The first step would be to block sign-in from the Admin Center.
 
<img src="https://github.com/user-attachments/assets/ca3f8605-8208-4895-b7c4-fde92aa0e674" height="80%" width="80%"/>

Licenses must then be removed so the company isnt paying for any inactive users, this is done by simply clearing the checkboxes.
If there is any relevant data in the users mail needed for operations to continue, it can be turned into a shared mailbox for the relevent users to have access to. This could be requested by a manager if required.

<img src="https://github.com/user-attachments/assets/55200140-2cf6-4d20-bea6-27d20926f72f" height="80%" width="80%"/>

Finally the User account can be deleted. Deleted account data is held for 30 days before being deleted permanently.
<img src="https://github.com/user-attachments/assets/39157e69-f5fe-46e2-be0f-bd62e77570bb" height="80%" width="80%"/>

<br />
 




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
