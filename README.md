# helpful-tips-and-commands
This folder is a collection of helpful tips and commands I use for work
## Table of Contents
- [Terraform](#terraform)
- [AWS](#aws)
- [Github](#github)
- [Mac](#mac)
- [Docker](#docker)
---
# Terraform  
1. Watch terraform `plan` :building_construction:

    ```bash
    terraform plan | wc -l
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

# Github 
1. Check Github `account` :octocat:

    ```bash
    git config -l
    ```
2. Check current working `branch` 🌱

    ```bash
    git rev-parse --abbrev-ref HEAD
    ```
# Mac   
1. Copy current path to clipboard :clipboard:

    ```bash
    pwd | pbcopy
    ```
2. Check Spotify Status :musical_note:

    ```bash
    curl -i https://open.spotify.com
    ```
# Docker 
1. List images before created before a specific image :whale:   

    ```bash
    docker images --filter "before=image1"
    ```
