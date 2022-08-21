<h2>Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</h2>

 Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons.  Artemis has a REST API based software package that is in need of a security evaluation.  They have hired Global Rain to evaluate their software for potential security issues and to recommend fixes for those issues.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

The security of their software was comprehensively evaluated using a variety of methods to ensure that no vulnerabilities were missed. This comprehensive approach is what I feel the value of using Global Rain as a consultant partner is. Using a manual method as well as an automated vulnerability scan ensures that secure coding is addressed as well as known vulnerabilities. Secure coding is so important because it addresses the aspects of security that often can't be found with automated tooling. It ensures that the code will be intrinsically secure becuase of good coding practices. When code is secure, it reduces the likelyhood that the software will be compromised.  Compromised software can ruin a company's reputation, profitability and even significantly harm its users.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

In working through the vulnerability assessment process there was one particular section that was challenging. Not challenging in regards to difficulty, but challenging in regards to the sheer amount of work involved. The number of vulnerabilities that we had to go through to find resolutions was quite large and that process ended up being tedious.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

In my experience, there are several places where security can be layered in. The first is in the transport mechanism used. This includes things like securing the communication from the user to the software, the software to any data sources like databases, and between layers of the software itself.  Strategies like ensuring transport encryption is used for commincation between the users, the application, and the database.  Ensuring that authentication and authorization is in place for the applicaiton is critical.  By employing multiple layers of security, the application can be protected even if one of these layers is breached or compromised.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

Three primary methods were utilized to ensure the code was functional and secure.  First, to address functionality, thorough code testing was performed to ensure that the application performed the tasks that were necessary for proper operation.  Second, the code was scanned using an automated vulnerability tool. Third, the code was scanned manually for vulnerabilities.  Once the data from these assessments were gathered, code refactoring to address any vulnerabilities was performed and the manual and automated scans run again to verify no new vulnerabilites were introduced.  This process is iterated until no new vulnerabilities exist and all previous vulnerabilities have been addressed.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

For programs that utilize java for a programming language, the Maven OWASP plugin would be very useful. It finds vulnarabilities automatically and provides a detailed report of the found issues.  I would also utilize the OWASP secure coding practices quick reference guide and the vulnerability flowchart. All of these tools and resources help to ease the burden of finding vulnerabilities and help to make software more secure.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would showcase the final written report that was generated from the results of the thorough analysis of the code provided.  While technical proficiency in programming languages is the minimum cost of entry to a career in computer science, I find that employees who have the ability to generate clear, concise documentation and can convey their ideas to others have the most success.