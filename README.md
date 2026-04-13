This is an Active Directory with Samba on linux

// Hyper-V //

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

-Join linux client to a the domain

---Hyper-V uses eth0 as default network adapter, we have to change it to make work ---

--- Made another Virtual Machine in other computer got access to my Active Directory Domain Services, both computers will be in the same network and the switch disconected from the access point ---

-- Domain policies are empty, maybe cuz we're not in the Client Machine with the applied policies, it only affects the computers but not the entire domain --

-GPO's issues fixed, is about gran permision to groups in order to allow applyng group policies inside them, very stupid is you ask me, I have to remove ther Normalusers gpo completly and create a new one from zero, but it works, It takes 5 hours to have done --

