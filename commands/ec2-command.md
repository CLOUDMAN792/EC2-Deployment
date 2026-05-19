# EC2 Deployment Commands

## SSH into EC2

#!/bin/bash
SSH -i ~/Downloads/newkeypair.pem ec2-user@54.83.82.11


## Update Packages

#!/bin/bash
sudo yum update


## Install httpd

#!/bin/bash
sudo yum install httpd -y


## Check httpd Status

#!/bin/bash
sudo systemctl status httpd
