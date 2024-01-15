-: The Linux Active Directory Installer Utility :-

( Tested on Ubuntu 22.04 LTS Server , 23.10 )

This Utility will Configure the Linux Server to act as Active Directory Domain Controller
This will Install Following Packages on the Server

AD-Provision , Import-UGO, Remove-UGO

* AD-Provision : This command will Install SAMBA, LDAP, WINBIND, Kerberos, DNSUtils, Net-Tools etc. and further configure the system for AD-DC Environment.
  You Just have to give Hostname, IP, and Domain name on first screen then on 3 Kerberos (pink) screens DomainName, HostName, HostName respectively.
  All other Configuration will be taken care.

* Import-UGO : This Command will create Users, Groups, OUs provided in CSV file.
* Remove-UGO : This Command will delete Users & Groups provided in CSV file.

  >Step 1:
          Download the 'AD-Provision-Install' and upload to server through stfp,wincp,filezill etc. like utility
  
  >Step 2:
          Run the utility by command './AD-Provision-Install' on '#' prompt (with root access).
          If it not runs change the permission by command 'chmod +x AD-Provision-Install' then run command again.
  
  >Step 3:
          Above command will install 3 commands/utilities AD-Provision, Import-UGO, Remove-UGO.

  @To Do Administrative Tasks , join an Windows 10 Client to the domain and install RSAT (Remote Server Administrative Services) on it.
  So you will get the Windows Server Like Administrative Utilities like 'Active Directory Users & Computers','Group Policy Management' etc.

  You may refer : https://youtu.be/ySehJeBKAFI
  

  
          

