# Project 5 - CI/CD Pipeline with CodePipeline

## What I Built
Automated deployment pipeline that connects GitHub 
to AWS EC2. Every time code is pushed to GitHub, 
the menu site updates automatically.

## AWS Services Used
- CodePipeline (orchestrates the pipeline)
- CodeDeploy (deploys files to EC2)
- IAM Role (gives AWS permission to access GitHub and EC2)
- EC2 (my-first-server)

## How It Works
1. Push code changes to GitHub
2. CodePipeline detects the change automatically
3. CodeDeploy copies new files to EC2
4. Nginx restarts and serves the updated menu

## Files
- appspec.yml - instructions for CodeDeploy
- scripts/install_dependencies.sh - restarts Nginx after deploy
- index.html - the restaurant menu

## What I Learned
- What CI/CD means and why companies use it
- How CodePipeline connects GitHub to AWS
- How appspec.yml instructs CodeDeploy
- Why automation removes human error from deployments

