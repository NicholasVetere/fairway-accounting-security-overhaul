# Fairway Accounting Group – Security Overhaul

## Project Overview

This was my final cybersecurity capstone project at Coding Temple. I created a virtual network for a fictional accounting firm with 45 employees, assessed security weaknesses, and implemented improvements to better protect its systems and information.

The goal was to gain hands-on experience with network security, access management, security monitoring, and troubleshooting.

## Technologies Used

- pfSense – Firewall configuration and network segmentation
- Windows Server 2022 – Active Directory, DNS, and file services
- Windows 11 – Domain-joined workstation and security testing
- Ubuntu Linux and Apache – Web server and HTTPS configuration
- Wazuh – Security monitoring and log analysis
- Kali Linux and Nmap – Network scanning and validation
- VirtualBox – Virtual lab environment
- Bash – Basic security testing automation

## Security Improvements

- Separated the web server from the internal network using pfSense.
- Corrected unnecessary Active Directory group membership and file permissions.
- Strengthened password requirements and account lockout settings.
- Configured HTTPS for the client portal.
- Required SMB signing on the file server.
- Configured Wazuh to monitor Windows authentication events.
- Tested network connectivity and security controls to verify the changes.

## Testing and Results

I performed Nmap scans, checked file permissions, tested network restrictions, and reviewed security events in Wazuh.

During a controlled test, three failed login attempts generated Windows security events that were detected in the Wazuh dashboard.

## Challenges and Troubleshooting

Some of the main challenges involved DNS resolution, firewall rules, Wazuh services, and Ubuntu virtual machine startup issues.

Working through these problems helped me better understand how networking, operating systems, and security tools depend on one another.

## Project Scope

This project was completed in a simulated environment, not a production business network. Some security controls were implemented and tested, while others were documented as future recommendations.

## Documentation

The repository includes project documentation, architecture diagrams, security testing results, and a proposed incident response plan.
