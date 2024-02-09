**Improving Secure Coding Practices: A Practical Guide for Developers**

Worked on by Karen Mai and James Ma

As Software Engineers, we need to value and consider computer security whenever we write code because we want to build applications that will not be easily break due to malicious practices. Often before approving a pull request, we should all review a few items that ensure secure best practices. In this project, we will delve into secure coding practices. The main deliverable for this project will be through a github repository where we will keep subfolders that will each explain an aspect of good coding practice. 

**What we would like in the main README.md (here)**
1. Introduction
   - Overview of the importance of secure coding practices in software development
   - Brief explanation of common security vulnerabilities and their impact
2. Background
   - Explanation of why secure coding is crucial in preventing security breaches
   - Overview of common types of vulnerabilities (e.g., SQL injection, XSS, CSRF) and their consequences
   - Introduction to secure coding guidelines and standards (e.g., OWASP, CERT)
3. Objectives
   - Creating a comprehensive guide to secure coding practices with coding examples
   - Demonstrating the importance of secure coding through practical case studies like something that happened
   - Developing a tool or technique to assist developers in writing secure code, something similar to coverlay
4. Agenda
   - Brief structure of what the different subfolders will be so that it could be like a taster before one wants to dive into a folder to learn more about it 

**Core Component/Idea for Subfolders**
We will be aiming to have about 4 subfolders so that we can sort of have a variety. 
   - Syntax and Structure
     - Using Private Access Modifier, Encapsulation, Immutable Classes, Private Constructors, and Private Methods
   - Secure Input Handling
     - Explanation of the risks associated with user input and how to mitigate them (e.g., input validation, parameterized queries)
     - Code examples and best practices for handling different types of input (e.g., text, file uploads)
   - Valid Libraries
     - Only use secure coding libraries like Apache Common Codes for secure encoding and hasing so that there is OWASP ESAPI input validation and output encoding.
   - Secure Communication
     - Perform secure communication over network so that data is encrypted in transit
     - Will require usage of OAuth of JWT when performing a client-server communication
   - Data Sanitization and Validation
     - Explanation of the importance of data validation and sanitization in preventing injection attacks (e.g., SQL injection, XSS)
     - Techniques for validating and sanitizing user input to prevent injection vulnerabilities
   - Error Handling and Logging
     - Importance of proper error handling and logging in identifying and mitigating security incidents
     - Guidelines for securely logging sensitive information and handling errors gracefully without exposing sensitive details

**Beyond the Core**
   - Integration with Development Environments
     - Suggestions for integrating secure coding practices into popular IDEs (e.g., Visual Studio Code, IntelliJ IDEA)
     - Development of plugins or extensions to automate code analysis and suggest security improvements
   - Continuous Integration and Testing
     - Strategies for incorporating security testing into the CI/CD pipeline
     - Recommendations for using tools like static code analysis, dynamic application security testing (DAST), and fuzz testing

**Stretch Goal**
   - Development of our own secure coding assessment tool (similar to coverlay but specific to security)
     - Proposal for creating a tool that evaluates code against secure coding standards and provides actionable feedback to developers
     - Make it a tool where when you run this file, it will scan through all your files and do like a sanity checklist
     - Some items on this sanity checklist: have we used private, is there a secure HTTP connection, have we used a library that is not approved like Apache, has there been enough code coverage, and others. We will give like a percentage, like rating it to be 85% secure because it is missing the following requirements.
    
     
