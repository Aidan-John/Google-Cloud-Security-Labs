## Activity overview

Firewall rules play a crucial role in cloud network security because they control which traffic is allowed to enter and leave your cloud environment. The nature of cloud networking is ever changing and complex. Organizations' needs change, new cloud resources are added or removed, and new vulnerabilities are discovered. This means that you'll need to continually adjust and maintain the configuration of firewall rules to adapt with these changes.

Tracking and managing critical updates in your cloud environment can be challenging. Luckily, you can manage the configuration of your cloud resources by leveraging **infrastructure as code (IaC)**. IaC is the provisioning and managing of infrastructure through using reusable scripts. It can be used to automate workflows such as updating firewall rules.

Terraform and Cloud Shell make it easy to manage and update firewall rules efficiently. By writing desired firewall rules in Terraform configuration files and executing Terraform commands in Cloud Shell, you can ensure that your network security policies remain consistent and version-controlled. This approach will help you maintain and track changes over time.

In this lab, you'll learn how to clone a Terraform repository and deploy a VPC network and firewall.

## Scenario

Cymbal Bank's new banking application is ready to be deployed. It needs to be hosted on a Virtual Private Cloud (VPC). Your team lead, Chloe, would like to define and provision the application's network infrastructure using Terraform. Terraform can be used to securely provision cloud infrastructure in a way that's repeatable and consistent. This way, you can easily and quickly make any required changes. You have been tasked with using Terraform to create a network and firewall rules.

Here’s how you'll do this task: **First**, you’ll activate the Cloud Shell. **Then**, you’ll clone the Terraform repo. **Finally**, you’ll deploy the VPC network and firewall.
