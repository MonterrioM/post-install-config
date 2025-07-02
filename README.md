<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Email Settings
  Set up SMTP and IMAP/POP3 to allow ticket creation and responses
- Set Up Departments and Teams
  Create departments (e.g., IT Support, HR) and assign agents to streamline ticket routing.
- Customize Help Topics and Ticket Forms
  Define custom help topics and fields to collect specific issue details from users.

- Enable User Authentication and Roles
		Configure user permissions, agent roles, and access controls to secure the ticketing system.
- Enable System Notifications and Auto-Responses
	Set up automated responses for ticket creation, assignment, and resolution updates

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/GsONM9m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This screenshot shows me logging into the osTicket web interface for the first time after a successful installation. The login screen displays the help desk title at the top, with fields for the admin username and password. After entering my credentials, I clicked “Sign In,” accessing the osTicket dashboard. This confirms that the system is properly installed and ready for ticket management, customization, and deployment in a real-world support environment.
<br />

<p>
<img src="https://i.imgur.com/b9LKoer.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This screenshot captures the process of setting up a Service Level Agreement (SLA) within the osTicket admin panel. I navigated to the Admin Panel > Manage > SLA Plans, then clicked “Add New SLA Plan.” I configured response and resolution times based on ticket priority levels to ensure timely support. This setup helps define expectations, improve accountability, and streamline ticket resolution workflows for better help desk performance and customer satisfaction.
</p>
<br />

<p>
<img src="https://i.imgur.com/cl09BPm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This screenshot shows the configuration of Help Topics in the osTicket admin panel under Manage > Help Topics. I created custom categories to organize incoming tickets based on common support requests such as "Technical Support," "Billing Issues," and "Account Access." Each topic can trigger specific workflows or SLA plans. Setting up help topics improves ticket routing, ensures faster responses, and enhances the overall efficiency of the support system.
</p>
<br />
