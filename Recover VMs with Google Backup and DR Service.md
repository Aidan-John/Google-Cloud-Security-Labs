## Activity overview

Business continuity and disaster recovery planning is critical for sustaining business operations while recovering from a significant security incident, natural disaster, or disruption.

Google Cloud Backup and DR Service is a cloud-based backup and disaster recovery solution that enables the backup and recovery of data , to support quick resumption of critical business operations.

After Backup and DR performs an initial full backup, your data (general applications, VMware VMs, Compute Engine VMs, databases, and file systems) is backed up incrementally, updating and storing any data that has changed since the last backup.

The initial configuration of the Backup and DR service includes the deployment of a management appliance that can take up to 45 minutes to complete. This task has been carried out for you prior to the lab startup. Once the Backup and DR Service are enabled, you can explore the Backup and DR management console and protect workloads.

This lab guides you through the steps of discovering and protecting a Compute Engine instance, and finally mounting a fully-functional new Compute Engine instance from the backup image to a new location.

## Scenario

Cymbal Bank's Incident Response Team successfully responded to the security incident and contained the unauthorized access. Hannah and the rest of the Incident Response Team are working on implementing recovery actions to restore the affected virtual machines (VMs). You have been asked to assist with this.

Here’s how you’ll do this task: **First**, you’ll connect to the Backup and DR management console. **Next**, you’ll create and validate a backup plan template. **Then**, you’ll discover and add a Compute Engine instance to the Backup and DR management console. **Finally**, you’ll restore a Compute Engine instance in two different Google Cloud projects.
