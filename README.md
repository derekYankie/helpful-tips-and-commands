# helpful-tips-and-commands
This folder is a collection of helpful tips and commands I use for work
## Table of Contents
[Mac Commands](#mac-cmd)
[Github Commands](#github-cmd)
[AWS Commands](#docker-cmd)
<a name="github-cli"></a>
### Mac Commands 💻
1. Check IAM `account` or role 
<a name="mac-cli"></a>

    ```bash
    pwd | pbcopy
    ```
---
### Github Commands 🐙 
1. Check Github `account`

    ```bash
    git config -l
    ```
2. Check current working `branch` 🌱

    ```bash
    git rev-parse --abbrev-ref HEAD
    ```
---
### AWS Commands ☁️ 
1. Check IAM `account` or role 
<a name="aws-cli"></a>

    ```bash
    aws sts get-caller-identity
    ```
2. List instances 
<a name="aws-cli"></a>

    ```bash
    aws ec2 describe-instances
    ```
---

