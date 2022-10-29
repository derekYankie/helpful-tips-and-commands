# helpful-tips-and-commands
This folder is a collection of helpful tips and commands I use for work
## Table of Contents
- [Terraform](#terraform)
- [Mac](#mac)
- [Github](#github)
- [AWS](#aws)
- [Docker](#docker)
---
# Terraform  
1. Watch terraform `plan` :building_construction:

    ```bash
    terraform plan | wc -l
    ```

# Mac   
1. Copy current path to clipboard 💻

    ```bash
    pwd | pbcopy
    ```

# Github 
1. Check Github `account` :octocat:

    ```bash
    git config -l
    ```
2. Check current working `branch` 🌱

    ```bash
    git rev-parse --abbrev-ref HEAD
    ```

# AWS 
1. Check IAM `account` or `role`☁️ 

    ```bash
    aws sts get-caller-identity
    ```
2. List instances 

    ```bash
    aws ec2 describe-instances \
    --filters Name=availability-zone,Values=us-east-2c
    ```

# Docker 
1. List images before created before a specific image   

    ```bash
    docker images --filter "before=image1"
    ```
