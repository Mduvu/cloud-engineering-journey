# Project 4 - Infrastructure as Code with CloudFormation

## What I Built
Recreated EC2 web server infrastructure using a 
CloudFormation YAML template instead of manual console clicks.

## AWS Services Used
- CloudFormation (stack: menu-stack)
- EC2 Instance (t3.micro, Ubuntu 24.04)
- Security Group (ports 80, 443, 22)

## What I Learned
- How to write CloudFormation YAML templates
- How IaC makes infrastructure repeatable and trackable
- How one file can replace hours of manual console work
- The difference between manual and automated deployments

## Challenges & Solutions
- YAML indentation must be exact or the stack fails