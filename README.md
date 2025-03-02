# CS305Projects

  The client, Artemis Financial, is a consulting company that works with its customers to create personalized financial plans. This can include savings, retirement, investments, and insurance. Due to the highly sensitive nature of these plans the company needs to have high security for communications when dealing with customer’s information such as social security numbers, full names, and account numbers. There is no information that the client is a US-based only company, therefore there is reason to believe that international transactions are an option. Due to the client being in the financial sector, there will be governmental restrictions. This is because the financial sector is one of the most heavily regulated industries. Future and present external threats are any attacks on client’s information that Artemis Financial represent. This can include DDoS attacks, malware, phishing, and data breaches. Modernization requirements to consider, such as open-source libraries and evolving wed application technologies need to be maintained to check for bugs and any security vulnerabilities frequently to protect from attacks. 

Which part of the vulnerability assessment was challenging or helpful to you?
  One issue I had was that my port 8443 was in use. So I had to manually find the code for it in my command prompt, then terminate it. 
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  Within the RestController I added extra security in the form of an authentication and encryption algorithm, known as SHA-256. I used MessageDigest to get the instance of SHA-256, then calculated the digest hash of the input. BigInterger is used to exceed the limits of fixed sizes. Therefore, it is great to use when encryption is necessary. HexString is then used to convert the byte array of the digest into a hexadecimal string and returns that hash. After creating a self-signed certificate, I then had to update the application.preperties file. This included using the same alias, password, store and store type as I did with the creation of the certificate. This is meant to turn HTTP into HTTPS for even more added security

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  By the code running properly, this showed that it was functional. I also completed a dependency check.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  I would make this project public and let them see the entire project. This will show my ability for code securely and run checks.

