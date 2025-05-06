## Activity overview

**IAM**, or **Identity and Access Management**, is a collection of processes and technologies that help organizations manage digital identities in their environment. With IAM, access control is managed by defining the identity of users and their roles in relation to available resources. Resource access permissions are not granted directly to individual users. Instead, users are assigned to roles that are then given to authenticated principals. While the term "members" was used in the past, IAM now refers to these individuals as principals, although some APIs still use the previous terminology. There are three types of IAM roles in Google Cloud:

- **Basic roles**: Roles historically available in the Google Cloud console. These roles are Owner, Editor, and Viewer.
- **Predefined roles**: Roles that give finer-grained access control than the basic roles. For example, the predefined role Pub/Sub Publisher (roles/pubsub.publisher) provides access to only publish messages to a Pub/Sub topic.
- **Custom roles**: Roles that you create to tailor permissions to the needs of your organization when predefined roles don't meet your needs.

In this lab, you’ll learn how to create and manage Identity and Access Management (IAM) custom roles.

## Scenario

As part of its migration plan, Cymbal Bank is incrementally deploying its workflows to the cloud. One of these deployments includes a database which stores sensitive customer billing and invoice data. Before this database can be deployed, it needs to go through a comprehensive third-party audit. The auditors need access to this database to complete this audit. They need to be granted the appropriate permissions necessary to complete their job. Your team lead, Chloe, has tasked you with leveraging IAM to implement access control to this database for the audit group.

IAM is a fundamental component of cloud security and it will play a pivotal role in your task. The members of the audit team will require designated roles with restricted access, exclusively for viewing and listing the database contents. Your task, as outlined by your team lead, entails the precise configuration of user access to align with these strict requirements.

Here’s how you'll do this task: **First**, you’ll create a role and assign the required permissions. **Next**, you’ll assign the new role you have created to a user. **Finally**, you’ll verify that the role you created has been granted.
