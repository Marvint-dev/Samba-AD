¡Hi, this is my first time here! 

I just planning to improve my skills, so thats the reason why I decided to create this repository

This is an Active Directory with Samba on linux

I will uploading my advantanges


-Users Database:
It includes, roles and permisions ----- Completed! (Only exported from db in csv format)

*  Directly connected database to AD Server --- to do


- Group policies: Works god only adding the users to their respective OU!!

-Automatic scripts for register all users in a row, considerating their origin table ----- Completed!
--- Group policies can be managed by a domain administrator using the client side --- Completed!
Clients obtain IP address by DHCP request, and the IP address from DNS Server, no manual ip config ---- Completed!

- Fixed local admins permission
- Only Domain Admins can edit active GPO's

-Add and configure an FTP-Server

-Define a company name and design a logo

-Join linux client to a the domain- This is becoming difficult, but I'll use GNS3 to improve in that --- this sh*t don't work 🤬

-Linux client now is on domain! but still have some minor issues, first we'v to fix the usser loggon

-Linux client on domain is completely worth! , oem installation has provoking minor isssues but I highly recommend don't use this kind of install for domain join purposes ----- now is working good

-Fixed linux mint domain issues, auth and sssd services, finally AD users can logon into the system with his own credentials ---- Fully worth , minor issues: sudo

-- Discovered an issue performing a disk import from my computer with the vmdk extension but looks is about VBox version issue, trying an older version (7.0.26) is completely worth!

---- Learned how to export and make .vdi , .vmdk VirtualBox disk into .vhdx Hyper-V disks, using quemu-img tool, need some dependencys but's very useful ---

---Hyper-V uses eth0 as default network adapter, we have to change it to make work ---
--- Made another Virtual Machine in other computer got access to my Active Directory Domain Services, both computers will be in the same network and the switch disconected from the access point ---
-- Domain policies are empty, maybe cuz we're not in the Client Machine with the applied policies, it only affects the computers but not the entire domain --


