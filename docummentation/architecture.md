# System Architecture

## Overview

This project demonstrates deployment of an amazon Linux server on AWS EC2.

The server was configured using SSH and httpd web server was installed successfully.

---

## Architecture Flow


Local Computer
      |
      | SSH Connection
      |
AWS EC2 amazon Server
      |
      | httpd
      |
Hosted Web Application




## Components Used

- AWS EC2
- amazon Linux
- SSH
- httpd
- GitHub



## Networking

The following ports were enabled:

- Port 22 (SSH)
- Port 80 (HTTP)



## Security Configuration

Security groups were configured to allow remote server access securely.



## Result

The httpd web server was successfully deployed and accessible through the EC2 public IP address.