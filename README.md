# CS-305-Mod-8-Journal

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
The client is, Artemis Financial, a consulting company that develops individualized financial plans for their customers. Artemis Financial wanted
their custom software to use the most current and effective software security. The issue that needed to be addressed was to
add a file verification step to their web application to ensure secure communications. When the web application is used to transfer data, they will need a data verification step in the form of a checksum. You must take their current software application and add secure communication mechanisms to meet their software security requirements.

### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
When I had found security vulnerabilites, I generated a report that listed each vulnerability. This report states if a current solution exists to the problem. The importance of coding securely is to be able to gain trust of clients. While losing money do to poor softweare security, losing the trust of clints is almost irrecoverable.

### What part of the vulnerability assessment was challenging or helpful to you?
Having Maven be used in conjunction with a dependency-check report is super simple. However trying to identify False-Positives was a very daunting task. To try and identify the list of all the vulnerabilites to see if it was a simple library mix-up took alot of effort.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
By updating all the libraries in the POM to the most current version solved many of the security issues. In the future I will reference the OWASP top 10 to help further identify which issues are a critical threat to the business, and which can wait on for updated libraries.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
By having a report before making any modifications, allowed me to run the same report after refactoring the code. By comparing these two reports I could tell that I did not introduce any new vulnerabilites when refactoring the code. By developing the code incrementally and running it often I could tell it was functional and by running the tests I cold tell it was secure.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Using the idea of incremental development, test often, fail often, helped me identify any points of failure while developing my code. It is crucial to identify points of failure early so they can be fixed immediately.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this project I would show future employers that I understand how to identify and report on security issues in their current codebase. I would also like to show future employers that I can make edjustments to improve security while keeping the program fully functional.
