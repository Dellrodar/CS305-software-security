# CS305-software-security
A repo for showing past software security projects.

# Artemis Financial – Practices for Secure Software

## Portfolio Reflection

### 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that develops customized financial plans for its clients. Their priority was to secure sensitive financial data and ensure their application could safely communicate with clients over the internet. The company wanted me to identify security vulnerabilities, apply encryption, generate certificates for secure communication, and refactor their code so it complied with modern secure software practices.  

### 2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?  

I performed a thorough dependency check and identified vulnerabilities in outdated libraries. I upgraded them to patched versions and validated the fixes. I also applied strong encryption with AES and implemented HTTPS. Secure coding prevents data breaches, builds client trust, and protects both the company’s reputation and financial stability.  

### 3. Which part of the vulnerability assessment was challenging or helpful to you?  

The most challenging part was analyzing the dependency-check report and filtering out false positives versus legitimate vulnerabilities. This process was also very helpful because it showed me how to prioritize risks and address them with upgrades or configuration changes.  

### 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?  

I increased security by generating a certificate for HTTPS, deploying AES encryption, updating outdated dependencies, and validating inputs. In the future, I would continue using tools like OWASP Dependency-Check, combined with static and dynamic code analysis, to evaluate vulnerabilities and choose effective mitigation techniques.  

### 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?  

I ensured functionality by running the Spring Boot application after refactoring and verifying that endpoints responded securely over HTTPS. To confirm security, I ran a new dependency-check scan and validated that no new critical vulnerabilities were introduced. Functional and secondary testing together confirmed both correctness and security.  

### 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Key resources and tools included the AES encryption standard, certificate generation in PowerShell, and the OWASP Dependency-Check Maven plugin. Helpful practices included input validation, secure error handling, and updating dependencies regularly. These tools and methods will remain valuable in both coursework and real-world projects.  

### 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  
I could share the secure software practices report, the certificate generation process, and the dependency-check results. These demonstrate my ability to apply encryption, set up secure communications, perform vulnerability assessments, and follow industry best practices when refactoring code.  
