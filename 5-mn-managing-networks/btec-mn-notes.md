Learning Outcomes

- 1. Know about networking management tools and technologies
- 2. Understand network management functions
- 3. Be able to carry out network management activities

Unit Contents

- 1. Know about networking management tools and technologies
  - Network technologies
    - Operating Systems
    - Protocols
    - Layout
    - Devices
  - Networking operating systems
    - Windows
    - Linux
  - Networking protocols
    - SNMPv3
    - ICMP
  - Layout
    - Cabling
    - Topologies
    - Wireless
  - Network devices
    - servers
    - workstations
    - Interconnection devices
    - Network cards
    - Vendor specific hardware
  - Networking tools & purpose
    - Tools
      - HP Openview
      - Cisco Works
      - Wireshark
      - Angry IP
      - Using system software eg to find network assets
    - Purpose
      - Fault management
      - Performance management
  - Emerging technologies
    - Server virtualization
    - Video on demand
  - Impact of emerging technologies
  - Enhanced capabilities
    - Faster
    - Greater storage capacity
    - Improved control
  - New work methods
    - Mobile working
    - Home working
    - Web centric applications
    - Ease of use
- 2. Understand network management functions
  - Network management functions:
    "Network configuration is the process of maintaining and organizing the information of the network components. If the network needs repairing, any modifications, expansions or upgrades the network manager can refer to the NCM database and to decide what the best course of action is. The database contains the locations and network addresses of all hardware devices; it also contains information about the programs, versions and updates installed in network computers.
    Network configuration is a major aspect of setting a network up, the network will be regularly tweaked to improve performance and solve any issues that arise."
    - Configuration management
      - Configuration management is taken to include issues such as change control, hardware inventory mapping, software inventories and customization of systems.
    - Fault management
      - Fault management includes events, alarms, problem identification, troubleshooting, diagnosis and fault logging.
    - Performance management
      - Performance covers capacity planning, availability, response times, accuracy and throughput.
    - Security management
      - Security discusses policy, authorization, exceptions, logging etc.
    - Accounting management
      - Finally, accounting includes asset management, cost controls and payment for services.
  - Performance Variables
    - Network throughput
    - User Response Time
    - Line Utilization
    - Other activities eg
      - Planning
      - Designing
      - Installing
    - Network Operations
      - Security
      - Data Logging
      - Checking Performance
      - Traffic
    - Reporting
- 3. Be able to carry out network management activities
  - Regular maintenance activities
    - Backup and Restore files
    - User account creation and deletion
    - Design and develop login scripts
    - Virus scans
    - File cleanup
  - Tools
    - To manage performance or fault find
      - SNMP / HP Openview
  - Documentation
    - Work logs
    - Log resources used
    - System testing
  - Configuration options
    - User accounts location eg choosing server and setting rights
    - Drive mappings
    - Other eg virus scanning options
  - Security features:
    - VPN access
    - Firewall management
    - Access control lists
    - Device hardening
      "In computing, hardening is usually the process of securing a system by reducing its surface of vulnerability, which is larger when a system performs more functions; in principle a single-function system is more secure than a multipurpose one. Reducing available ways of attack typically includes changing default passwords, the removal of unnecessary software, unnecessary usernames or logins, and the disabling or removal of unnecessary services.
      
      Hardening is the process to eliminate a means of attack by patching vulnerabilities, turning off non-essential services and configuring system with security controls such as password management, file permissions and disabling unused network ports. 
      
      The hardening activities for key management systems involve several steps to form layers of protection."
      - Remove all non-essential services and programs
        - Every program is a potential entry point for a hacker. Cleaning out unnecessary programs and utilities from the computer can reduce the attack surface area. Programs such as FTP, telnet, and Rlogin should not be used. If the program is classified as non-essential for the company, it shouldn’t be allowed because hackers might take advantage by backdoors and security holes. This also involves disabling network ports and services that are no longer required for the operation of the system. Disabling removable media, or disabling automatic run features on removable media and enabling automatic malware checks upon media introduction can also help in reducing the attack surface area of the system.
      - Upgrade and implement latest security patches
        - In the digital age, it is important to realize that there is no perfect security. Vulnerabilities are often discovered in systems and appropriate security patches are released to fix the issue. Patch management is essential for maintaining and improving key management systems security posture. The security policy and standards for the organization should specify the process for obtaining, testing and deploying patches. Testing must be carried out on a confined system before deployment to ensure no functional problems are introduced by the patch
      - Implement Least Privilege on user accounts and file systems
        - Using the principle of least privilege to control access to sensitive system features, application, files and data. This also includes limiting user accounts to those needed for legitimate operations and disabling or removing accounts that are no longer required. The concept of least privilege is an important factor in designing a hardening checklist for servers.
      - Password Management
        - In a hardening checklist, password management includes the use of complex password, password expiry, password re-use period, password maximum days, password minimum length, and password change period. One should note that the hardening checklist should comply with the password policy of the organization. Replacing all default passwords and keys with strong passwords and randomly generated keys (or implement strong authentication, such as smart cards) should be part of the hardening checklist for key management system.
      - Logging and auditing
        - System, application and security logs should be enabled in the server. For example, in a linux server, by default syslog stores data in /var/log/ directory. It is useful to analyze unauthorized access or hacking attempts. Tamper-evident logs are recommended for proof of compliance to internal and/or external requirements.
      - Enabling additional security features and configuration option
        - Additional security features such as Mandatory Access Control (MAC) provided by SELinux can help in enforcing limitation on network and other programs. The hardening checklist for key management system should specify how these features can be enabled and the configuration settings for the process. It is also mandatory to configure and harden services such as SSH or RDP. The SSH hardening should detail how the SSH settings should be configured. The NIST publication on ‘A framework for Designing Cryptographic Key Management System’ recommends enabling optional security features as appropriate and selecting other configuration options that are secure.
    - Continuous policy review
    - Forensic analysis
    - User rights
  - Security policies and procedures
    - Periodically review user access and rights
    - Penetration testing
    - Security
    - Audits
    - Review firewall
    - Access control list policies
  - Configuration Management