<img width="810" height="287" alt="OSIMG" src="https://github.com/user-attachments/assets/25c932d7-25e9-40ef-a511-0f2c60595df6" />

# osTicket-prereqs and Installation 

This project is a hands-on tutorial and walkthrough that demonstrates the prerequisites, installation, and basic configuration of osTicket, an open-source help desk ticketing system commonly used in IT support environments.

The goal of this project is to simulate a real-world IT help desk setup using a cloud-hosted Windows machine and to demonstrate practical system administration skills relevant to entry-level IT and Help Desk roles.


📌 Project Summary

🔹 Project Type

This project is a technology implementation and walkthrough that documents the full installation process of osTicket, from environment setup to verification and testing.

🔹 Languages Used

~PowerShell (basic system checks and administration)
~HTML / PHP (osTicket backend – configuration only, no custom coding)

🔹 Environments Used

~Microsoft Azure
~Windows 10 (21H2)
~Internet Information Services (IIS)

🔹 Technologies / Applications / Services Used

~osTicket
~Microsoft Azure Virtual Machines
~Internet Information Services (IIS)
~PHP Manager for IIS
~MySQL Database
~Remote Desktop Protocol (RDP)

🌐 Environments and Technologies Used

~Microsoft Azure (Virtual Machines / Compute)
~Remote Desktop
~Internet Information Services (IIS)

💻 Operating Systems Used

~Windows 10 (21H2)

📋 List of Prerequisites

~Microsoft Azure subscription
~Windows 10 Virtual Machine
~Internet Information Services (IIS)
~PHP 7.4
~PHP Manager for IIS
~MySQL Server
~osTicket installation files

⚙ Installation Steps

Step 1: Create and Access the Virtual Machine

A Windows 10 virtual machine is created in Microsoft Azure with sufficient resources (4 vCPUs). The VM is placed in a dedicated resource group and accessed using Remote Desktop. This virtual machine serves as the environment where osTicket and all required services will be installed and configured.

<img width="985" height="634" alt="VM" src="https://github.com/user-attachments/assets/83613337-a5df-457c-857d-8299dcca8afb" />

Step 2: Configure the Web Server and Dependencies

Internet Information Services (IIS) is installed and configured with CGI enabled to support PHP applications. Required components such as PHP, PHP Manager for IIS, the IIS Rewrite Module, Visual C++ Redistributable, and MySQL are installed. PHP is registered within IIS, and necessary PHP extensions are enabled to ensure osTicket can run properly.


<img width="584" height="413" alt="IISIMG1" src="https://github.com/user-attachments/assets/248e7dff-96b7-46ed-a12c-6cbfcdaf51a3" />

Step 3: Install, Configure, and Secure osTicket

The osTicket application files are deployed to the IIS web root directory and configured for use. File permissions are set, configuration files are renamed, and the web-based installer is completed to define the help desk name, database connection, and administrative settings. Once installation is complete, the setup directory is removed, configuration files are locked down, and both the admin and end-user portals are tested to confirm the system is fully operational and secure.


<img width="282" height="400" alt="OSTick" src="https://github.com/user-attachments/assets/17717e3b-9051-4cea-8c37-e454307057d4" />

<img width="314" height="417" alt="OSINT" src="https://github.com/user-attachments/assets/d3ed3578-a819-4bd2-b156-3de25cf0bd22" />

<img width="511" height="447" alt="IISM" src="https://github.com/user-attachments/assets/2221cd36-64e7-48ff-96bf-4333b197b511" />


<img width="607" height="712" alt="OSHOme" src="https://github.com/user-attachments/assets/95fe7805-373e-4530-a079-ce61da1f336e" />
