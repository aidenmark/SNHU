# CS305
SNHU CS 305 Software Security

Aeriel Denmark | Demory | Portfolio | Sun 3/2/25

- Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting firm that develops customized financial plans for its clients, covering savings, retirement, investments, and insurance. They wanted to enhance the security of their web application by adding a file verification step. The goal was to implement a cryptographic hash algorithm to ensure data integrity during transmission.

- What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I successfully identified and implemented a cryptographic hash function to verify data integrity, ensuring that transmitted files remain unaltered. Secure coding is critical because it prevents unauthorized access, protects sensitive financial data, and ensures compliance with industry standards. Strong security practices build client trust and protect companies from financial loss and reputational damage.
  
- Which part of the vulnerability assessment was challenging or helpful to you?

Running the OWASP Dependency-Check tool was helpful in identifying vulnerabilities in third-party dependencies. However, analyzing the report and determining whether these issues impacted the security of my changes was challenging. Understanding how to interpret vulnerability reports and differentiate between critical issues and false positives was a valuable learning experience.
  
- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by implementing HTTPS, generating and applying a self-signed SSL certificate, and using SHA-256 for checksum verification. These enhancements ensure encrypted communication and data integrity. In the future, I would use static code analysis tools like OWASP Dependency-Check and follow best practices like least privilege access and regular security audits to assess vulnerabilities.
  
- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I verified functionality by testing the checksum endpoint over HTTPS and ensuring it correctly generated hash values. To check for security vulnerabilities, I ran the OWASP Dependency-Check tool to scan for potential issues. I also performed manual code review and tested secure communication by inspecting the SSL certificate in the browser.
  
- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used Java Keytool for certificate generation, OWASP Dependency-Check for vulnerability scanning, and Spring Security to enforce HTTPS and authentication. These tools and practices are essential for implementing secure software development and will be useful in future cybersecurity and software engineering projects.
  
- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would showcase my implementation of cryptographic security measures, including secure hash functions, HTTPS enforcement, and vulnerability assessments. These demonstrate my ability to enhance software security, work with encryption technologies, and follow best practices for secure coding, which are valuable skills in software development and cybersecurity roles.
