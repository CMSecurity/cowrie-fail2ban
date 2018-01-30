# cowrie-fail2ban
Ban IP's after to much succeeded sessions in cowrie

## Installation
Clone the repo to your machine. if you're only using fail2ban for cowrie, you can just copy the files to `/etc/fail2ban/`.  
Otherwise you might want to merge the cowrie-section from jail.local with your config.  
Afterwards, restart the fail2ban service.

## Requirements
Fail2ban needs to be installed
