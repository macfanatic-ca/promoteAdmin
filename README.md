## PromoteAdmin
Promotes the current user to Administrator permenetly, as long as their part of a designated AD/LDAP group.

## TemporayAdmin
Promotes the current user to Administrator temporarily, with an expiration time set within the script's variables. Removal of privileges occures on the machine locally, no internet access is required. 

*Both scripts are designed to be **run as root**.  Typically this would occur when deployed using Casper or Munki.*