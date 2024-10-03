# post-install-config<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
- SysAdminsConfigure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking
- Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)
- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset[
Other

<h2>Demonsration and Configuration Steps</h2>

(https://imgur.com/FzoU9hD)<br />
In this image, you can see that you can configure different types of roles for each group 


(https://imgur.com/yztIqJf)</p>
In this image, you can see how to configure differnt departments within each group and who can edit and view differnt types of tickets

(https://imgur.com/4Mxi62s)
In this image you can see how to go about configuring different teams for differnt types of projects 

(https://imgur.com/5Od9Gri)
Here you can see how to go about seting differnt types of SLA and setting the grace period for differnt types 

(https://imgur.com/XOjk8Zs)
in this image, you can put different types of help topics or for when users create the ticket for the agent to complete
