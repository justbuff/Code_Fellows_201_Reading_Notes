# Imaging, Backup, and Recovery

Veeam Backup Free Edition is a free tool for backing up virtual machines and Hyper-V environments. Veeam can be summarized into three categories:

VeeamZIP- Creates an ad-hoc backup of a running VM. All that needs to be done to create a backup is specify the VM you want to backup and where the backup file goes. The file is compressed and about half the size of of the VM's actual disk usage. VeeamZIP is useful when you need to update, archive, or copy a VM. 

Powerful and flexible restores- Veeam Supports a number pf recovery scenarios such as the recovery of an entire VM. Veeam can also restore VM files, disks, guest OS files, and individual Microsoft Exchange and SharePoint items.

Quick Migration (VMware)- Migrates a live VM bewteen hosts or datastores with minimal downtime. Quick Migration does so without requiring clusters, shared storage, or advanced functionality and works even in slow or high latency connection environments. 

Additional Veeam features include:

Native tape support- Veeam can store individual files and VM backups on standalone tape drives and tape libraries (physical or virtual).

Advanced support for VMware vCloud Director- Veeam implements enhanced backup and recovery for vCD, with VM and vApp restoration directly back to the original or new vCD location. 

Veeam Explorer for Microsoft SharePoint and Microsoft Exchange- Veeam Explorer is a free tool which allows the user to search for individual items inside backups of SharePoint and Exchange VMs, recover items quickly and without agents, and send restores items as email attachments to specific users.

Parallel processing of virtual disks within VMs- Veeam can handle several virtual disks simultaneously inside one VM. This improves VeeamZIP performance and reduces the workload on storage resources.

Ignoring empty blocks- VeeamZIP detects and does not backup empty blocks within virtual disks.

Hardware-accelerated compression- VeeamZIP uses a default compression algorithm to take into account available CPU resources on a backup server which significantly reduces the workload on backup proxies and reduces server usage.



