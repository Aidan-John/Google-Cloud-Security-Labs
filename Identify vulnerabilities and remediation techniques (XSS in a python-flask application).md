## Activity overview

Identifying vulnerabilities and implementing remediation techniques is crucial for helping ensure the security and stability of various systems and applications. Many applications and systems handle sensitive information, such as personally identifiable information, financial records, or intellectual property. Identifying vulnerabilities helps protect this sensitive data from unauthorized access and potential breaches. Addressing vulnerabilities early in the development process is generally more cost-effective than dealing with security breaches later. The cost of remediating a vulnerability is often much higher than the cost of preventing it in the first place.

As a security analyst, regularly scanning for vulnerabilities can help identify and address weaknesses before malicious attacks, thus mitigating potential threats proactively. It provides insight into an application’s attack surface, helping enable you to understand potential avenues of exploitation and prioritize critical areas for improvement.

In this lab, you'll not only learn how to set up and run a vulnerable application but scan it for vulnerabilities.

## Scenario

Cymbal Bank has developed a new banking application for its corporate clients that is set to be hosted and deployed on the new cloud infrastructure. The Chief Information Security Officer (CISO), Javier, wants to prioritize the security of this application before it is launched and customer-facing. Your team lead, Chloe, has tasked you with identifying and mitigating any application vulnerabilities for this new application. You'll use the Web Security Scanner in Google Cloud to scan the application for vulnerabilities pertaining to a top OWASP® web application vulnerability known as Cross-Site Scripting (XSS).

Here’s how you'll do this task: **First**, you’ll create a static IP address and launch a virtual machine. **Then**, you’ll deploy the vulnerable application. **Next**, you’ll set up and run the application. **Then**, you’ll access and scan the application. **Finally**, you’ll fix the vulnerabilities and re-scan the application.
