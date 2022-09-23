# helpful-tips-and-commands
This folder is a collection of helpful tips and commands I use for work
## Table of Contents
- [Mac](#mac)
- [Github](#github)
- [AWS](#aws)

# Mac   
1. Copy current path to clipboard 💻

    ```bash
    pwd | pbcopy
    ```
---
# Github 
1. Check Github `account`🐙

    ```bash
    git config -l
    ```
2. Check current working `branch` 🌱

    ```bash
    git rev-parse --abbrev-ref HEAD
    ```
---
# AWS 
1. Check IAM `account` or `role`☁️ 
<a name="aws-cli"></a>

    ```bash
    aws sts get-caller-identity
    ```
2. List instances 
<a name="aws-cli"></a>

    ```bash
    aws ec2 describe-instances \
    --filters Name=availability-zone,Values=us-east-2c
    ```
---

