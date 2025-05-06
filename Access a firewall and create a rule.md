## Activity overview

The assets within a cloud environment need to be protected from unauthorized access. To address this, security professionals use **perimeter protection** which refers to the security measures implemented to defend the edge of a network or system against unauthorized access and cyber threats. One type of perimeter protection includes using firewalls to manage and secure network traffic entering and leaving a cloud environment. Firewalls help protect trusted internal networks (like a company's private network) from untrusted external networks (such as the Internet). Firewalls examine both incoming and outgoing network traffic based on predefined rules to either allow or block specific data packets. This is crucial for helping maintain application security, traffic control, compliance, and policy enforcement.

In this lab, you‘ll access a firewall and create rules to test the security of a server and make modifications as necessary.

## Scenario

Cymbal Bank has a demo web server that is provisioned on an existing Virtual Private Cloud (VPC) network. Your team lead, Chloe, is concerned about the security configurations of this web server and wants you to analyze the inbound network traffic to the web server and block connections to unnecessary ports using firewall rules. You have been tasked with analyzing the firewall rules for this web server and testing its connection. To complete this task, you will need to create several firewall rules, connect to the web server, and analyze the logs associated with the network connections.

Here’s how you'll do this task: **First**, you'll create a firewall rule to allow network traffic to the demo web server. **Then**, you’ll generate HTTP network traffic to the server and analyze its network logs. **Next**, you’ll create and test a new firewall rule to deny HTTP traffic to the server. **Finally**, you'll analyze the firewall logs to verify that the new firewall rule works as intended.
