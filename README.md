# CS-305-Module-Eight-Journal-
## 🔒 CS 305 Module Eight Journal  
### Portfolio Submission — Secure Software Development  

**Student:** Matthew Baerg  
**Course:** CS 305 — Secure Software Development  
**Date:** 10/25/2025

---

### 🧩 Repository Contents  
- **Artifact Submitted:**
  - ✅ Artemis Financial Vulnerability Assessment Report  
  - ✅ Artemis Financial Practices for Secure Software Report  


### 💭 Reflection  

**Who was the client and what issue did the company want you to address?**  
The client, **Artemis Financial**, is a financial services company focused on providing secure investment advice and financial planning tools for its customers. Their concern was that their web application lacked strong data security measures. They requested a full vulnerability assessment and a secure code refactor to ensure that client information and financial transactions were properly protected using modern encryption and security practices.

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely?**  
I effectively identified weaknesses through dependency scanning and source code review using tools like **OWASP Dependency Check**. I documented each vulnerability with a clear description, risk rating, and mitigation strategy. Secure coding is crucial because it prevents unauthorized data access and protects both company and client information. Strong software security adds trust, reduces liability, and strengthens the company’s reputation.

**Which part of the vulnerability assessment was challenging or helpful to you?**  
The most challenging part was interpreting the vulnerability reports and determining which issues were truly exploitable versus informational. Learning to evaluate the severity of vulnerabilities and prioritize remediation based on risk taught me how to balance security with practicality.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide on mitigation?**  
I implemented multiple layers of defense, such as **TLS encryption**, **checksums**, and **secure coding standards** to prevent injection attacks. In the future, I would continue to use automated tools like OWASP Dependency Check, static analysis tools (SAST), and manual code reviews to identify vulnerabilities early in the development cycle.

**How did you make certain the code and software application were functional and secure?**  
After refactoring the code, I rebuilt and tested the application to ensure all functions remained intact. I re-ran the dependency check tool to verify that no new vulnerabilities were introduced. Additionally, I reviewed encryption implementations and configuration files to ensure secure communication and data handling.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**  
I used **Maven**, **OWASP Dependency Check**, and **Spring Boot best practices** to identify and mitigate vulnerabilities. These tools and techniques taught me to integrate security directly into the development process rather than treating it as an afterthought. Concepts like input validation, encryption, and secure configuration will be essential in all future projects.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**  
I would show employers the **Artemis Financial Vulnerability Assessment Report**, demonstrating my ability to identify and document security issues, and the **refactored secure application**, which showcases my ability to implement encryption, manage dependencies, and maintain code functionality while improving security. Together, these artifacts highlight both my analytical and technical capabilities in secure software development.

---

### ✅ Summary  
This project strengthened my understanding of secure coding, vulnerability assessment, and remediation techniques. By analyzing dependencies, applying encryption, and ensuring functional integrity after refactoring, I learned how to design and maintain secure software systems that align with real-world industry standards.

---

