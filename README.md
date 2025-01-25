# Ethical Hacking Project: Vulnerable Virtual Machine

[Download](https://drive.google.com/drive/folders/1DvkHXa61_mL4UEsY6U7Ovbe-Vbh5SR4W?usp=drive_link)

This project involves the design, configuration, and implementation of a **vulnerable virtual machine** intended for ethical hacking and penetration testing practice. The VM is configured with deliberate vulnerabilities to simulate realistic attack scenarios, providing opportunities to gain remote access and escalate privileges to root.

## Project Overview

1. **VM Design**:
   - Based on **Ubuntu Server 20.04 LTS (64-bit)**, compatible with **Oracle VirtualBox**.
   - Exposes multiple services, some of which have intentional vulnerabilities to allow penetration testing for:
     - Gaining local access through exploitative methods
     - Escalating privileges to root

2. **High-Level Vulnerability Implementation**:
   - **Local Access Paths**:
     - **Easy Path**: Exploit a service with weak credentials
     - **Intermediate Path**: Exploit an outdated version of a web service vulnerable to SQL injection
     - **Hard Path**: Chain multiple exploits, such as XSS leading to session hijacking
   - **Privilege Escalation Paths**:
     - **Easy Path**: Misconfigured file permissions exposing sensitive data
     - **Intermediate Path**: Exploit a known vulnerability in an outdated program
     - **Hard Path**: Exploit a buffer overflow in a custom C program

### Report
A detailed report is included to document:
- A description of the introduced vulnerabilities
- The step-by-step explanation of how a penetration tester could gain root access using each vulnerability

---

## Download and Usage Instructions
1. [Download](https://drive.google.com/drive/folders/1DvkHXa61_mL4UEsY6U7Ovbe-Vbh5SR4W?usp=drive_link) and import the VM file into Oracle VirtualBox
2. Try to exploit all possible vulnerabilities
3. Follow the attack path scenarios outlined in the report

---

## Disclaimer
This VM should only be used in controlled environments. The vulnerabilities introduced in the VM are intentional and should not be replicated outside the scope of this project.
