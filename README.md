The Linux Active Directory Installer Utility 

(Tested on Ubuntu 22.04 LTS Server!)

This Utility will Configure the Linux Server to act as Active Directory Domain Controller
This will Install Following Packages on the server

AD-Provision , Import-UGO, Remove-UGO

* AD-Provision : This command will Install SAMBA, LDAP, WINBIND, Kerberos, DNSUtils, Net-Tools etc. and further configure the system for AD-DC Environment.
  You Just have to give Hostname, IP, and Domain name on first screen then on 3 Kerberos (pink) screens DomainName, HostName, HostName respectively.
  All other Configuration will be taken care by the utility.

* Import-UGO : This Command will create Users, Groups, OUs provided in CSV file.
* Remove-UGO : This Command will delete Users & Groups provided in CSV file.

