# Data Restoration, Startup Repair, and Secure Disposal

## SSD Data Recovery

SSD failures are difficult to detect since they do not emit mechanical noise like HDD do and can fail silently. There are still detectable indicators of HDD failure (read/write limit or physical issues): 

- Bad blocks. In an SSD, “bad blocks” are storage segments that impede data storage and retrieval functions through memory corruption or physical damage. Symptoms include saving, reading, and moving files may result in failure, active applications may operate slowly or frequently crash, the user may receive prompts to repair the file system, and general performance may steadily decrease especially when handling large files. The best course of action is to run software that searches for physical defects. If the software discovers physical damage, it's best to back up essential files and replace the SSD.

- File system repair. If a computer or file system requires repair but physical defect software shows no damage, this could indicate an issue with the connector port. Backup important files then proceed to repair the system- Windows OS use file system repair, Mac OS users can use Disk Utility, and Linux users can run the fsck utility.

- Crashing. If a computer crashes while booting up but seems to work normally after several reboots, the SSD is probably failing.  Run software to assess the performance and health of your SSD or reinstall the OS after the data has been cleared on the partition set.

- Read-only mode. It is possible for SSDs to cease functioning except in read-only mode. In the event that an SSD will not operate except to perform read-only functions, the drive is most likely corrupted.

Fixing an SSD that is failing to perform properly depends on the source of its issues. If there is a physical problem like hardware damage or degraded flash cells, the SSD may need to be replaced. However, if the dysfunction derives from a logical error like bad blocks, software malfunctions, malware, or outdated firmware a handful of techniques may achieve SSD recovery.

Some recovery options include:

- Formatting the drive and redownloading the operating system.
- Power cycling the SSD. First, unplug the SATA data cable, but leave the power cable in. Leave the power on for half an hour, then turn it off for 30 seconds. Turn the power back on again for another half hour. Finally, turn it off for another 30 seconds. Turn the power back on and reconnect the data cable. If power cycling has been effective, the SSD will be back up at this point.
- Idling in the boot menu. This method is similar to power cycling, except that while the power is on during the half-hour intervals, the computer should be left to idle in the boot menu. On a PC, boot into BIOS and sit at the BIOS screen. On a Mac, get to the boot menu by turning on the computer while holding down the ALT key.
- Updating SSD firmware. When firmware is bad, it can affect the drive’s ability to access, read, and write data. Run a firmware update tool to check whether the SSD has the latest version.
- Updating drivers. In Windows, simply check the Device Manager, go to Disk Drives, and right-click the SSD to update the driver. After rebooting, you may be able to see the revived SSD.

### Is it possible to recover data from a failed SSD?

Many of the above processes for reviving failed SSDs and evaluating poor drive performance allow SSD users to prevent complete data loss in the first place. If physical or firmware damage is too extensive the drive may not be able to be revived. In other situations, a corrupted drive may come back on with the right approach, but its data may still be lost. 

Many SSDs utilize TRIM, an Advanced Technology Attachment (ATA) command that helps an OS know which data blocks it can clear. This function increases both the performance and service life of an SSD by speeding up data writing, but TRIM erases data completely upon deletion which means the data is gone before the block has been overwritten by a new file. 

Data recovery is still possible as many data recovery programs have recovery wizards that scan SSDs for deleted files and allow for restored partitions or individual files. There are also businesses that employ tech experts who decrypt SSDs and recover data using the best method for your specific SSD failure and drive manufacturer.

### SSD protection best practices 

Data recovery is a complicated process that can cost time and money that could be better spent elsewhere. Precautions should be taken to catch and address SSD problems before they become full-blown failures. Some precautions include:

- Download a program from a selection of existing free software options designed to monitor SSD health by tracking operating temperature and performance metrics.
- Buy strategically. Many SSDs come equipped with S.M.A.R.T. (Self-Monitoring, Analysis, and Reporting Technology) that warns users of potential failure and prompts them to take preventative measures.
- Have a backup strategy. Backup data regularly and routinely.

## How to Erase a Hard Drive using DBAN

Darik's Boot And Nuke (DBAN) is an entirely free data destruction program used to completely erase all the files on a hard drive. DBAN has to run while the operating system isn't in use so it needs to be burnt to a disc (CD, DVD, USB) and ran from there.

To begin with DBAN, download and save the ISO file from the website. Next, properly burn DBAN to a disk or USB drive and then boot into the disk or USB. Follow the prompts on the DBAN program and choose an option from the main menu. The F3 key will open DBAN's Quick Commands screen, where the commands will automatically assume you want to remove all the files from all the connected drives and will immediately start deleting after you enter the command. The Enter key will choose Interactive Mode, which lets you customize exactly how DBAN will erase files, as well as which hard drives it will wipe. After choosing the desired options, wait for DBAN to erase the hard drive, then verify that it was successfull by viewing the "DBAN succeeded" message.
