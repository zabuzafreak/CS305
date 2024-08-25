# CS305
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
  Artemis Financial is a consulting company that develops individualized financial plans for its customers. The company wanted us to modernize its operations while   ensuring that their software was secure.
What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
  We used a tool to check for dependencies and their vulnerabilities. It is easy to implement and run a scan of the code. It is important to code securely   to avoid potential attackers gaining access to people's personal information. A company with security you can trust is a company that people will invest   in and a company that more customers will be attracted to.
Which part of the vulnerability assessment was challenging or helpful to you?
  Learning how to use the maven depenency check tool was very helpful. It is always important to know the risks of the packages you use.
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  One simple but effective measure is to add try and catch blocks. It is important to ensure that any time we parse string data we don't potentially give    access to easy overflow attacks with unwanted or garbage data. Securing these error catching structures with exactly what data we will and won't accept    goes a long way.
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  Re-running the dependency check tool is the easiest way. As the refactored code had to include new packages, that also has the potential to introduce      new vulnerabilities.
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  Encryption is really interesting to me. Now that I know how to generate keys from strings, it will be interesting to see where I can take this.
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  I don't think my assignments hit a level of quality that I would be comfortable using as a portfolio piece. I think they have given me new tools to work   with and from that I hope to create some more personalized software that I would be comfortable walking them through and using as a portfolio piece.
