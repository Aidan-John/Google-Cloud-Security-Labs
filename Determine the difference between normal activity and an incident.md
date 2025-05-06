## Activity overview

Event Threat Detection is one of Security Command Center's (SCC) services. Event Threat Detection is a log-based threat analysis that continuously monitors Google Cloud logs for potential threats. When Event Threat Detection identifies suspicious activity, it generates a finding that you can investigate.

In this lab, you’ll analyze findings in the Google Cloud Security Command Center and examine related events in Cloud Logging.

## Scenario

Recently, the security team discovered two threat findings relating to suspicious activity with user accounts. The threat findings were promptly investigated and remediated. One of the findings was determined to be benign user activity while the other finding was confirmed as malicious. Your team lead, Chloe, has tasked you with examining the details behind each finding so that you can understand the difference between normal activity and malicious activity. To do this, you'll recreate the malicious activity to trigger IAM detectors, analyze the logs associated with both threat findings, and then remediate the malicious finding.

Here's how you'll do this task: **First**, you'll grant permissions to an external account to trigger an Event Threat Detection IAM finding. **Then**, you'll use the Security Command Center to access the two IAM findings. **Next**, you'll analyze details of the findings using Security Command Center and Cloud Logging to determine which finding is benign activity and which is anomalous. **Finally**, you'll remediate the finding related to the malicious IAM activity by adjusting the IAM settings.
