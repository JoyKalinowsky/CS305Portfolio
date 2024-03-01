# CS305
# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial was a consulting company that developed individualized financial plans for their customers, such as savings, retirement, investments, and insurance plans. 
The issue they wanted to address was adding a file verification step to their web application in the form of a checksum to ensure secure communications.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
When I found my client's software security vulnerabilities, I wasted no time in to look for solutions to these vulnerabilities. 
It is important to code securely because hackers can take advantage of insecure code to intercept company communications and eavesdrop on the data being transmitted. This can result in sensitive company information being compromised, such as payroll information and trade secrets.
Software security adds protection to a company's overall wellbeing because it makes it much more difficult for the company's online systems to be compromised by hackers. Considering the widespread use of the internet in modern society, this is crucial to a company's operations if they want to be able to stay up to date with current technology while still keeping their information safe. 

# What part of the vulnerability assessment was challenging or helpful to you?
One particularly challenging part of the vulnerability assessment was fixing the vulnerabilities detected in the report. 
I found that many of the vulnerabilities either surrounded code functionality that was not present in the code base or are currently outdated. 
This made it difficult to determine which vulnerabilities in my code needed my attention, as opposed to which vulnerabilities were not applicable. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by adding SSL encryption to the website. I used  to generate a certificate using Java's keytool application.   
I also imported libraries from OWASP to better secure my code against XSS attacks. In the future, I would do more research about all of the CVE vulnerabilities found in my code and use online resources such as the National Vulnerability Database to learn the best mitigation techniques to use for each vulnerability. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I made certain that the code and software application were functional and secure by building and then running my code with Maven software to make sure that the result was a SSL-encrypted website that depicted a SHA-256 encrypted hash value.
I checked to see whether I introduced new vulnerabilities with the help of the OWASP Dependency-Check tool. I used the OWASP Dependency-Check Maven tool to recompile my code and report vulnerabilities within it.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Some tools that I used that might be helpful in future assignments and tasks are the OWASP Java HTML Sanitizer, the OWASP Dependency-Check Maven tool, and Java's Keytool application.
I found these tools useful to protect against XSS attacks, find known vulnerabilities in my code, and generate certificates to encrypt the final deployed website. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would mainly show future employers my code. When presenting this assignment via Github to future employers, I will upload my code base alongside the Practices for Secure Software report so that future employers can see my work and how I used Spring and Maven software to create an SSL-encrypted website containing a SHA-256 hash value.
From this assignment, in addition to displaying the Practices for Secure Software report, I might show future employers my changes to the original code base as well as screenshots that display the impact of those changes.
