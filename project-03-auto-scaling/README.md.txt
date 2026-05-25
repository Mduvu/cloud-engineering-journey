# Project 3 - Auto Scaling Web App

## What i Built

Auto Scaling Group with Appliation Load balancer for the restaurant menu site.

## AWS Services Used

-Launch Template
-Auto Scaling Group (min 1, desired 2, max 2)
-Application Load Balancer (menu-alb)
-Target Group(menu-tg)
-CloudWatch metrics collection

## What i learned 
-How Launch Templates work as server blueprints
-How Auto Scaling maintains server health automatically
-How Load Balancer distributes traffic across servers
-Why health checks and availability zone matter

## Challenges and solutions
-SQL server AMI error - fixed by selecting correct Ubuntu AMI
-Had to create target group separately before ASG