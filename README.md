# cowrie-fail2ban
Ban IP's after too many connections to a [cowrie](https://github.com/micheloosterhof/cowrie) instance.  
In its default config, point the jail to your cowrie.log and it will ban a source IP if it connected more than 20 times in the last 12 hours. The IP will be banned for 12 hours.

## Installation
Clone the repo to your machine. if you're only using fail2ban for cowrie, you can just copy the files to `/etc/fail2ban/`.  
Otherwise you might want to merge the cowrie-section from jail.local with your config.  
Afterwards, restart the fail2ban service.

## Requirements
Fail2ban needs to be installed
