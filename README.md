CS 305 Portfolio Artifact – Artemis Financial Secure Software Project
Overview

This repository contains my completed Practices for Secure Software Report from CS 305. In this project, I improved the security of a Java web application by adding secure communication, using SHA-256 to verify data integrity, and following secure coding practices. I also tested the application to make sure everything still worked after the changes were made.

Client and Software Requirements

The client for this project was Artemis Financial, a company that handles sensitive financial information. They wanted their application to better protect customer data and improve security. My job was to update the application by adding HTTPS, creating a secure certificate, and using SHA-256 hashing to verify that data had not been changed.

Finding Security Vulnerabilities

One thing I think I did well was following secure coding practices instead of trying to build security features from scratch. I used Java's built-in security libraries, added HTTPS, and implemented SHA-256 for checksum verification. Secure coding is important because it helps protect customer information, reduces security risks, and makes software more reliable. For a financial company, these protections help build trust with customers and reduce the chances of costly security issues.

Challenges

The most challenging part of this project was working with certificates and configuring HTTPS correctly. It took some time to understand how the keystore and certificate worked together. At the same time, it was one of the most helpful parts because I learned how secure communication is set up in a real application.

Improving Security

I added multiple layers of security by enabling HTTPS, generating a self-signed certificate, using SHA-256 for data verification, escaping user input, and adding the OWASP Dependency-Check plugin to scan for vulnerable libraries. In the future, I would continue using tools like OWASP Dependency-Check along with code reviews and vulnerability scanners to help identify security issues and decide how to fix them.

Testing the Application

After making changes to the code, I tested the application to make sure everything still worked correctly. I checked that the /hash endpoint generated the correct SHA-256 checksum, verified that the application ran over HTTPS, and reviewed the code to make sure I didn't introduce any new security problems. I also configured dependency scanning to help identify any known vulnerabilities in third-party libraries.

Resources and Tools

Some of the tools and practices I used during this project were:

Java MessageDigest (SHA-256)
Java Keytool
HTTPS and SSL certificates
PKCS12 keystore
OWASP Dependency-Check
Maven
Manual code review and testing

These are all tools and practices I can use again in future software development and security projects.

Portfolio Reflection

This project is something I would feel comfortable showing an employer because it demonstrates several important skills. It shows that I can improve the security of an existing application, implement secure coding practices, work with HTTPS and certificates, use cryptographic hashing, and test my work to make sure it is both functional and secure. It also demonstrates that I understand the importance of protecting sensitive information in real-world software applications.
