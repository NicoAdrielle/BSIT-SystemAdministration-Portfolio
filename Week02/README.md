# Week 2 – Enterprise Infrastructure Planning

## Student Information

* **Name:** Nico Adrielle N. Montorio
* **Course:** Bachelor of Science in Information Technology (BSIT)
* **Section:** BSIT-4A
* **Date:** August 13, 2026

---

# Project Overview

This project presents an Enterprise IT Infrastructure Plan for **ABC Startup Solutions**, a fictional software development and IT consulting company with 20 employees.

The purpose of this project is to design an initial IT infrastructure for a startup company before the purchase and deployment of its technology resources.

The infrastructure plan covers:

- Company requirements
- Hardware inventory
- Software inventory
- Network equipment
- Network topology
- System administration roles
- Infrastructure recommendations
- Backup and security strategies
- Future expansion
- Personal reflection

---

# Learning Objectives

* Analyze the IT requirements of a small organization.
* Identify appropriate hardware, software, and networking equipment.
* Prepare organized enterprise IT inventories.
* Design a logical enterprise network topology.
* Understand the responsibilities of different System Administration roles.
* Develop infrastructure recommendations based on organizational requirements.
* Practice technical documentation using Markdown.

---

# Company Scenario

ABC Startup Solutions is a newly established software development and IT consulting company that provides customized software solutions, web and application development, database management, and technical support services.

The company operates on a single office floor with **20 employees** distributed across four departments:

| Department             | Employees |
| ---------------------- | --------: |
| Information Technology |         5 |
| Human Resources        |         4 |
| Finance                |         5 |
| Sales                  |         6 |
| **Total**              |    **20** |

The infrastructure was planned from the ground up to provide the company with reliable workstations, centralized services, secure network connectivity, data storage, backup capabilities, and room for future expansion.

---

# Hardware Inventory Summary

The proposed hardware infrastructure includes:

| Hardware               | Quantity | Purpose                         |
|------------------------|---------:|---------------------------------|
| Desktop Computers	 | 14       | Employee workstations 	      |
| Business Laptops       | 6        | Mobile workstations	      |
| 24-inch Monitors  	 | 20       | Employee displays 	      |
| Rackmount Server       | 1        | Centralized services	      |
| Business Router        | 1        | Network routing		      |
| Network Firewall       | 1        | Network security		      |
| Managed Gigabit Switch | 1        | Wired network connectivity      |
| Wireless Access Points | 2        | Wireless connectivity 	      |
| Network Printers       | 2        | Shared printing 		      |
| UPS                    | 2        | Power protection 		      |
| NAS Storage            | 1        | Centralized storage and backups |
| External Backup Drives | 2        | Offline backups   	      |
| Network Rack           | 1        | Network equipment organization  | 

The equipment was selected based on the requirements of each department and the company's current workforce while providing additional capacity for future expansion.

---

# 💻 Software Inventory Summary

The proposed software environment includes:

| Software	         | Purpose				 |
|------------------------|---------------------------------------|
| Windows 11 Pro         | Employee workstation operating system |
| Ubuntu Server LTS	 | Server operating system	  	 |
| Microsoft 365 / Office | Business productivity 		 |
| Visual Studio Code     | Software development 		 |
| Git 		         | Version control 			 |
| GitHub Desktop	 | Git repository management		 |
| VirtualBox 	         | Virtual machine testing 		 |
| Google Chrome 	 | Web browsing 			 |
| Microsoft Defender 	 | Endpoint security			 |
| AnyDesk 		 | Remote technical support 		 |
| 7-Zip 		 | File compression and extraction	 |

These applications provide the operating systems, productivity tools, development environments, security features, remote support capabilities, and utilities required for the company's daily operations.

---

# Enterprise Network Diagram

The enterprise network topology uses a centralized managed switch to connect the company's departments and shared network resources.

The internet connection passes through the **ISP Modem → Router → Firewall → 48-Port Managed Switch** before being distributed to the server, network printer, wireless access points, and individual departments.

![ABC Startup Solutions Network Topology](diagrams/VeltrixDigital-NetworkTopology.png)

**Figure 1. ABC Startup Solutions Network Topology**

---

# Technologies Used

* Draw.io / diagrams.net
* Microsoft Word
* Markdown
* Git
* GitHub
* Windows 11 Pro
* Ubuntu Server
* VirtualBox
* Microsoft 365
* Visual Studio Code

---

# Challenges Encountered

### 1. Planning the Hardware Requirements

Determining the appropriate amount of hardware required careful consideration of the number of employees and the responsibilities of each department. The equipment was selected based on actual organizational needs while also considering future expansion.

### 2. Designing the Network Topology

Creating the enterprise network topology required determining the correct connections between the ISP modem, router, firewall, managed switch, server, printer, wireless access points, and company departments. Organizing the devices around a centralized managed switch helped create a clear and scalable network design.

### 3. Planning for Security and Data Protection

The infrastructure needed to consider more than connectivity and hardware. Security measures, password policies, antivirus protection, backups, and access control also had to be included to provide a more complete infrastructure plan.

---

# Reflection

This project helped me understand that system administration involves more than troubleshooting computers and installing software. Proper planning must take place before equipment is purchased or systems are deployed.

I learned how hardware, software, networking, security, backup systems, and administration roles work together to support an organization.

The most challenging part of the project was designing the enterprise network topology because I needed to determine how the Internet, firewall, router, switch, server, NAS, wireless access points, and departmental computers should connect.

The project also taught me the importance of scalability. An infrastructure should not only solve a company's current requirements but should also provide opportunities for future expansion.

Overall, this project improved my technical planning, documentation, problem-solving, and system administration skills. The concepts learned from this activity can be applied to real-world IT environments where reliability, security, and proper planning are essential.

---

# References

* [Cisco – Networking and Certifications](https://www.cisco.com/)
* [Microsoft Learn](https://learn.microsoft.com/)
* [Ubuntu Server](https://ubuntu.com/server)
* [Red Hat](https://www.redhat.com/)
* [CompTIA](https://www.comptia.org/)
* [Amazon Web Services](https://aws.amazon.com/)
* [Google Cloud](https://cloud.google.com/)
* [CISA – Cybersecurity Resources](https://www.cisa.gov/)
* [PLDT Enterprise](https://pldtenterprise.com/)
* [diagrams.net](https://www.diagrams.net/)

---
