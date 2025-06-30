Secure Software Development Artifact – Artemis Financial
Overview

For this project, I worked with a fictional client, Artemis Financial, a company that required improvements in their software’s security posture. The client tasked me with identifying and addressing potential vulnerabilities in their Java-based application, ensuring secure communication, data integrity, and code quality.

What I Did and Why It Matters

I performed a secure software implementation using SHA-256 cryptographic hashing and enabled HTTPS using a self-signed X.509 certificate. I followed OWASP and industry best practices to secure the application and then conducted static code analysis using OWASP Dependency-Check (v12.1.0). Secure coding is essential in protecting data from unauthorized access and ensuring regulatory compliance. These enhancements not only prevent common security threats but also increase trust with users and stakeholders.

Challenges and Key Takeaways

The most helpful aspect of the project was conducting static analysis with Maven's OWASP plugin, which gave real-time insight into dependency risks. Configuring HTTPS with the self-signed certificate using Java’s keytool was initially challenging, especially ensuring compatibility with Spring Boot. Overcoming these issues helped me strengthen the application’s end-to-end security.

Security Enhancements and Testing

Security was layered through cryptographic hashing, HTTPS setup, encapsulated code design, and refactored error handling. I confirmed functionality and security by performing manual testing, reviewing for logic errors, and verifying browser lock icon for HTTPS validation. Post-refactoring, I ensured that no new vulnerabilities were introduced by re-running OWASP Dependency-Check.

Tools, Techniques, and Future Applications

I used the MessageDigest class from java.security, Java keytool for certificate creation, Spring Boot configuration for HTTPS, and OWASP scanning tools. These tools and techniques—along with coding principles like least privilege and defense-in-depth—will be valuable in future software development projects, particularly in security-focused roles.

Showcasing My Work

This artifact demonstrates my ability to implement secure code, conduct vulnerability assessments, and apply best practices in software development. I would present this project to future employers as evidence of my secure coding skills, ability to refactor existing applications, and comfort working with cryptographic standards, SSL/TLS configuration, and static analysis tools.
