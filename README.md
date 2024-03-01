# CS305
# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial was a consulting company that developed individualized financial plans for their customers, such as savings, retirement, investments, and insurance plans. 
The issue they wanted to address was adding a file verification step to their web application in the form of a checksum to ensure secure communications.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
When I found my client's software security vulnerabilities, I wasted no time in to look for solutions to these vulnerabilities. 
Software security adds protection to a company's overall  

# What part of the vulnerability assessment was challenging or helpful to you?
One particularly challenging part of the vulnerability assessment was fixing the vulnerabilities detected in the report. 
I found that many of the vulnerabilities either surrounded code functionality that was not present in the code base, or are currently outdated. 
This made it difficult to find vulnerabilities that I should actually be fixing. 

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by adding SSL encryption to the website. I generated a SHA-256 encrypted certificate using Java's keytool application.  
I also imported libraries from OWASP to better secure my code against XSS attacks. In the future, I would do more research about all of the CVE vulnerabilities found in my code, 
and would use online resources to decide whihc mitigation techniques to use. 

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I amde certain that the code and software application were fucntional and secure by 
I checked to see whether I introduced new vulnerabilities with the help of Maven. I used the OWASP Dependency-Check Maven tool to recompile my code and report vulnerabilities within it.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Some tools that I believe might be helpful in future assignments and tasks are the OWASP Java HTML Sanitizer and Java's keytool application.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would mainly show future employers my code. When presenting this assignment via Github to future employers, I will upload my code base alongside the 
