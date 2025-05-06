## Activity overview

A **false positive** is an alert that incorrectly detects the presence of a threat. False positives can be triggered by genuine and legitimate user activity. Security teams may spend lots of time and resources investigating false positive alerts only to discover that there is no real threat.

In this lab, you'll recreate the activity that generates a false positive alert. Then, you'll access and analyze the false positive threat using Security Command Center (SCC) and take action to address it. You'll be using two separate accounts in this lab: one account to trigger the false positive and another account to analyze and remediate the false positive.

## Scenario

Your team lead, Chloe, has been notified of a low severity security alert. The alert identified a service account with broad permissions using insecure key management practices through user managed keys. Upon further investigation it was found that Hank, the cloud architect, unintentionally triggered this alert. Hank was testing a new service account and accidentally created the key for the test user account. This alert was addressed and closed as a false positive.

Chloe believes this alert serves as a great example of a false positive alert. Chloe has tasked you with recreating the activity that triggered the false positive alert. You'll analyze the alert and then remediate it. The process of recreating the false positive serves as a valuable learning experience that will help you understand how and why the alert was triggered and how you can implement effective security policies to mitigate further false positive alerts.

Here's how you'll do this task: **First**, you'll recreate the false positive by creating a service account, assigning a role, providing a key, and activating the service account. **Then**, you'll use Security Command Center (SCC) to access the vulnerability finding related to activity you triggered. **Finally**, you'll take action to remediate the vulnerability finding and take action to remediate the false positive.
