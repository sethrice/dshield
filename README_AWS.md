Support for AWS AMI Linux is still work in progress. Please report issues.
As of last testing, you may loose ssh access.
Please note that you need to open port 12222 using an appropriate security policy. 

```
sudo yum update
sudo yum install git
git clone https://github.com/DShield-ISC/dshield.git
sudo dshield/bin/install.sh
sudo reboot
```