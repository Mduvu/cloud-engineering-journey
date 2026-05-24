# Project 1 - Restaurant Menu on EC2

## What i built
Deployed a static HTML restuarant menu on AWS EC2 using Nginx.

## AWS services used
-EC2 (ubuntu 26.04, t3.micro)
-Nginx web server
-Security Groups (port 80)
-Elastic IP

## Live URL
http:// 100.54.34.51

## What i learned
-How to launch and connect to an EC2 instance
-How to install and configure Nginx
-How security groups control traffic 
-Why Elastic IPs matter 

## Challenges 
- menu.html wasn't loading - fixed by renaming to index.html
- menu stopped loading after Elastic IP change - fixed by restarting nginx
- Nginx not Auto-starting - fixed with systemctl enable nginx 