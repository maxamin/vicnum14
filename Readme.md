# OWASP Vicnum Web Application

Vicnum is a vulnerable web application designed to demonstrate common web vulnerabilities such as Cross-Site Scripting (XSS), SQL Injections, and Session Management issues. This project is aimed at IT auditors and cybersecurity enthusiasts, providing a flexible platform for testing, learning, and enhancing web security skills. It's also ideal for Capture The Flag (CTF) challenges.

## Overview

The Vicnum project is part of the OWASP (Open Web Application Security Project) initiative, designed to simulate real-world vulnerabilities. This app helps security auditors understand how attackers exploit web-based vulnerabilities and how to mitigate them effectively.

**NOTE**: The original virtual machine file for this project is corrupted. You'll need to create a new virtual machine and attach the existing hard drive manually to proceed.

## Vulnerabilities Included

1. **Cross-Site Scripting (XSS)**  
   Allows users to inject client-side scripts into web pages viewed by other users.

2. **SQL Injection**  
   Demonstrates how malicious users can inject SQL queries via input fields to manipulate the database.

3. **Session Management Issues**  
   Highlights insecure session management practices, allowing attackers to hijack sessions and impersonate legitimate users.

## Getting Started

### Prerequisites

- **Virtualization Software**: Install any virtualization software (e.g., VirtualBox, VMware).
- **Existing Hard Drive**: You will need to manually attach the existing hard drive file to a new virtual machine.

### Steps to Set Up

1. **Create a New Virtual Machine**  
   - Install VirtualBox or VMware.
   - Create a new virtual machine with appropriate resources (e.g., 2GB RAM, 10GB storage).
   - Choose Linux as the OS (recommended Ubuntu 18.04+).

2. **Attach Existing Hard Drive**  
   - Attach the existing hard drive file from the corrupted virtual machine as the primary disk.

3. **Start the Virtual Machine**  
   - Boot the virtual machine and ensure all services (Apache, MySQL) are running properly.

4. **Access the Web Application**  
   - Open your browser and go to `http://localhost:8080` (or the IP address assigned to your virtual machine).
   - Use the login page to start exploring the vulnerabilities.

## Capture The Flag (CTF) Setup

This application is ideal for setting up CTF challenges. Security enthusiasts can try to exploit the listed vulnerabilities. You can create flags for successful exploitation of the following:

- XSS injection in the comment section.
- SQL Injection to bypass login authentication.
- Session hijacking using weak session management.

## Contributing

Feel free to contribute to this project by improving the existing vulnerabilities or adding new ones. You can fork the repository and submit a pull request.

## License

This project is licensed under the [OWASP License](https://www.owasp.org/index.php/License).

---

For more information, visit the official OWASP Vicnum project page:  
[https://owasp.org/index.php/Category:OWASP_Vicnum_Project](https://owasp.org/index.php/Category:OWASP_Vicnum_Project)
