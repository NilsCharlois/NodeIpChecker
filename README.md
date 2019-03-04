# NodeIpChecker

The main goal of this is to retrieve the public ip address of the raspberry pi and send it to an email address if the public ip address has changed.
It will use the following npm modules:
- node-cron to schedule a job on a daily basis
- sendgrip-nodejs to send the email
- fs to read a status file (current ip address)

Also, as this will be stored on a public repository, a private key will be generated locally to encrypt the sensitive data (need to find a npm module for that)

