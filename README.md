# WIL_2024
# WIL

README: Crossing the Digital Divide with a Simple Bridge in the uThukela District

**Project Overview**

This project aims to develop and implement a robust network infrastructure to provide reliable internet connectivity to the main hospital in the remote uThukela District of Kwazulu-Natal, South Africa. The hospital serves a wide range of patients and requires consistent access to the internet to support medical, administrative, and supply chain operations. By implementing a sustainable network extension from an existing connection, this project addresses the digital divide in a crucial area and enhances healthcare delivery capabilities.

**Project Objectives**

1. Reliable Network Infrastructure: Enables high-speed, dedicated connectivity to support hospital operations.
2. Sustainable Design: Designed for long-term use with minimal maintenance.
3. Security Measures: Equipped with firewalls and secure connections to protect sensitive patient and hospital data.
4. Training for Hospital Staff: Comprehensive training for ICT staff to support infrastructure maintenance and troubleshooting.


**Network Requirements**

* Number of Active Users: 100
* Building Distribution:
	+ Main Building: 30 users

* Wireless Access: Each building contains a lobby, a 200 sqft open space, where wireless access to the network is essential.
* Security: Only authorized personnel are allowed to access the wireless network.
* Distances between Buildings:
	+ Main Building to Building 1: 300 meters
	+ Main Building to Building 2: 90 meters
	+ Building 1 to Building 2: 70 meters
* Internet Connection: A high-speed cable Internet connection is available in the main building and must be shared among all users.
* User Devices and Printers: Each user possesses one computer device, and three high-speed printers are present in each building.

**Network Design**

* IP Network Table:
	+ Servers: 10.0.0.0 - 10.0.15.255
	+ Wireless Network: 10.1.0.0 - 10.1.15.255
	+ Printers: 10.2.0.0 - 10.2.15.255
	+ Core Router: 10.3.0.0 - 10.3.15.255
	+ VoIP: 10.4.0.0 - 10.4.15.255
	+ Management: 10.5.0.0 - 10.5.15.255
	+ CCTV: 10.6.0.0 - 10.6.15.255
* IP Address Schema:
	+ Core Router: 10.3.0.1/20
	+ Distribution Switch 1: 10.3.0.2/20
	+ Distribution Switch 2: 10.3.0.2/20
	+ Access Point 1: 10.1.0.1/20
	+ Access Point 2: 10.1.0.2/20
	+ Access Point 3: 10.1.0.3/20
	+ Server: 10.0.0.1/20
	+ Building 1 Users: 10.1.0.4 - 10.1.0.33/20
	+ Building 2 Users: 10.1.0.34 - 10.1.0.63/20
	+ Building 3 Users: 10.1.0.64 - 10.1.0.103/20

**Hardware Requirements**

* 1 core router
* 2 distribution switches
* 3 access switches
* 3 wireless access points
* 100 IP addresses
* 30 Ethernet cables
* 30 wireless access points

**Software and Licensing**

* Security software and licenses
* Network management software
* Internet sharing and monitoring software

**Security Measures**

* Authentication and access control systems
* Encryption and cybersecurity measures

**Cabling and Infrastructure**

* Additional cabling and infrastructure costs

**Training and Documentation**

* Training for staff
* Documentation for network configuration and management

**Budget Breakdown**

* Hardware: R501,400
* Software and Licensing: R20,000
* Security Measures: R25,000
* Cabling and Infrastructure: R15,000
* Training and Documentation: R15,000
* Total Project Budget: R576,400

**Timeline**

* Equipment Procurement: Within 4 weeks from project start
* Network Infrastructure Setup: Main Building: Within 2 weeks, Building 1: Within 2 weeks, Building 2: Within 2 weeks
* Security Implementation: Concurrent with infrastructure setup
* Internet Sharing Configuration: Concurrent with infrastructure setup
* IP Address Management: Concurrent with infrastructure setup
* Training and Documentation: Within 1 week after network setup completion
* Testing and Quality Assurance: Within 1 week after network setup completion
* Project Review and Finalization: Within 1 week after testing and quality assurance
