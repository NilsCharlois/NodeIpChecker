# NodeIpChecker

The main goal of this app is to retrieve the public ip address of the raspberry pi and send it to an email address if the public ip address has changed.
It will use the following npm modules:
- node-cron to schedule a job on a daily basis
- sendgrip-nodejs to send the email
- fs to read a status file (current ip address)
- request-promise to get an html file from a website like whatismyip

Also, as this will be stored on a public GitHub repository, a private key will be generated locally to encrypt sensitive data (need to find a npm module for that)


