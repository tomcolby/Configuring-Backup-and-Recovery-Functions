# Configuring-Backup-and-Recovery-Functions

In this lab, I will configure backup and recovery functions that support business continuity, disaster recovery, and high availability. I will begin by installing the Windows Server Backup feature and configuring a daily System State backup. I will then review the steps involved in restoring a Domain Controller from an existing System State backup. In Section 2, I will configure two web servers to use a common Network File System (NFS) share and set up load balancing on a pfSense firewall-router.

### Skills Learned
- Understand the relationship between business impact analysis, risk analysis, risk assessment, business continuity planning, and disaster recovery planning
- Install Windows Server Backup and configure a System State backup.

- Restore a Domain Controller from a System State backup.

- Configure a Linux NFS server and Linux NFS clients.
- Configure load balancing across redundant web servers.

### Tools and Software Used
- Windows Server Backup
- Wbadmin
- NFS
- vi Editor
- pfSense

### Topology
- DomainController01 (Windows: Server 2019)
- pfSense-dc (FreeBSD: pfSense)
- WebServer01 (Linux)
- WebServer02 (Linux)
- StorageServer01 (Linux)

### Lab Overview
STEP 1 of this lab has three parts, which should be completed in the order specified.
 
- I will install the Windows Server Backup server feature.
- I will configure Windows Server Backup to make a daily backup of the System State.

STEP 2
- I will configure a Network File System (NFS) share and set up load balancing for two redundant web servers.

<h2>Program walk-through:</h2>

## STEP 1
### Part 1: Install Windows Server Backup

<p align="center">

</p>

### Part 2: Configure a System State Backup
<p align="center">

</p>


### Part 3: Restore from a System State Backup
<p align="center">

</p>

## STEP 2
### Part 1: Configure an NFS Share

<p align="center">

</p>

### Part 2: Configure Load Balancing
<p align="center">

</p>


### Part 3: Verify Load Balancing
<p align="center">

</p>
