## Activity overview

Google Cloud services write audit logs that record administrative activities and access within your Google Cloud resources. Audit log entries help you answer the questions "who did what, where, and when" within your Google Cloud projects. Enabling audit logs helps your security, auditing, and compliance entities monitor Google Cloud data and systems for possible vulnerabilities or external data misuse.

In this lab, you'll investigate audit logs to identify patterns of suspicious activity involving cloud resources.

## Scenario

Cymbal Bank has officially migrated to its hybrid cloud solution and successfully deployed its workflows on the new cloud environment. Unfortunately, the Security Engineering team has been notified of a high severity alert involving unauthorized access to several of its cloud resources. This is alarming since malicious actors can use compromised cloud resources to exfiltrate data and launch attacks on other systems. It is your first time experiencing a security incident. Your team lead, Chloe, recognizes this as a valuable opportunity for you to learn the processes and procedures involved with incident response. You've been assigned to shadow and observe Hannah, an incident responder on the Incident Response Team which is a unit of the Security Engineering department. Hannah has provided you with access to the alert's logs which you'll use to investigate the malicious activity. You want to get a better understanding of the security incident so you have set up a test environment to recreate the incident and analyze the artifacts. You will use two separate user accounts: one account will generate the malicious activity, and the other account will be used to investigate the activity.

Here's how you'll do this task. **First**, you'll recreate the security incident by generating activity from the first user account. **Next**, you'll export the logs for further analysis. **Then**, you'll continue recreating the incident and generate additional user activity. **Finally**, you'll utilize BigQuery to analyze the logs.
