# Evaluation_Phase_3


![لقطة شاشة 2023-12-16 144832](https://github.com/bndrlslmy/Evaluation_Phase_3/assets/91160602/d0cee13e-facf-45e0-a8a5-01221301d0af)




# Overview
This project involves the configuration of three routers (Router0, Router1, Router2) and associated switches and PCs to establish a specified network topology. The configurations are aimed at creating a structured network environment for testing and development purposes.

# Configuration Details
## Router0 Configuration
Hostname: R0

Domain: ee462.kau.edu.sa

User Credentials:
Username: user
Password: 123456

Console Login: Local
Enable Secret: 123456

IP Addresses:
Gig0/0: 10.10.10.1/30
Gig1/0: 10.10.12.2/30
Gig2/0: 192.168.10.254/24

Post-Configuration: Save configuration and restart Router0

Testing Setup: Connect PC0 to R0

PC0 Configuration:
IP Address: 192.168.10.1/24
Default Gateway: 192.168.10.254

Switch0 Configuration:
IP Address: 192.168.10.200/24

## Router1 Configuration
Hostname: R1

Domain: ee462.kau.edu.sa

User Credentials:
Username: user
Password: 123456
Console Login: Local
Enable Secret: 123456

IP Addresses:
Gig0/0: 10.10.11.1/30
Gig1/0: 10.10.10.2/30
Gig2/0: 192.168.20.254/24

Post-Configuration: Save configuration and restart Router1

Testing Setup: Connect PC1 to R1

PC1 Configuration:
IP Address: 192.168.20.1/24
Default Gateway: 192.168.20.254

Switch1 Configuration:
IP Address: 192.168.20.200/24

## Router2 Configuration
Hostname: R2
Domain: ee462.kau.edu.sa

User Credentials:
Username: user
Password: 123456
Console Login: Local
Enable Secret: 123456

IP Addresses:
Gig0/0: 10.10.12.1/30
Gig1/0: 10.10.11.2/30
Gig2/0: 192.168.30.254/24

SSH Configuration: Configure SSH on VTY 0

Post-Configuration: Save configuration and restart Router2

Testing Setup: Connect PC2 to R2

PC2 Configuration:
IP Address: 192.168.30.1/24
Default Gateway: 192.168.30.254

Switch2 Configuration:
IP Address: 192.168.30.200/24
# Final Test
Use an SSH Client in PC0 to establish a connection to R2. Take a screenshot of the entire screen showing the list of commands in the configuration mode of R2.

# Instructions
Follow the configuration details for each router and associated devices.

Ensure that all devices are connected as per the network topology.

Test the configurations as specified in the 'Testing Setup' section for each router.

Perform the final test using SSH from PC0 to R2 and document the outcome.

# Contributions
Bander Saeed ALsolami
1935181
