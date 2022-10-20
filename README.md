# CS-305-Software-Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company that develops finacial plans for their customers. The financial plans that are provided are, savings, retirement, insurance and investments. They are interested in utilizing their RESTful API and securing it with the most current and effective software security.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I was able to find the vulnmerabilities easily using the Maven dependancy check. I was also able to suppress files that were false-positives in order to narrow in on the actual vulnerabilites that the program had. IT's very important to code securely, and always think when wrting code, how you can introduce new vulnerabilities. The value of having reliable and effective software security is high. If a company storing a clients personal information is not reliable at securing that information, than that compnay had no trust from the client and therefore will not succeed.

What part of the vulnerability assessment was challenging or helpful to you?
I suppose identifying vulnerabilities that were already present in the code base that was provided to us. It is a new ability to learn how to identify vulnerabilities without using a dependancy check tool. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
The only way to increase layers of security isd to identify which vulnerabilities exist. One way of doing it is by using a dependancy chack toool on the code base. Another way to do it, and honestly my prefered way, would be to reverse engineer the code and locate discrepancies that way. 

How did you check to see whether you introduced new vulnerabilities? 
I ran multiple dependancy checks and suppressed any false-positive results that I found. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I relly prefered to use the maven dependancy check tool. I thought that was very helpful in locating the dependancies, suppressing false positives and finding fixes for the other dependancies. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show that I was able to identify vulnerabilites present in the source code that was provided. I could also show that I was able to update the souce code as needed to eliminate a lot of the dependancies that were listed.
