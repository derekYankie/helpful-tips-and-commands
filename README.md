# helpful-tips-and-commands
This folder is a collection of helpful tips and commands I use for work
## Table of Contents
[Github Commands](#github-cmd)
[AWS Commands](#docker-cmd)
<a name="github-cli"></a>
### Github Commands 🐙 
1. Check Github `account`

    ```bash
    git config -l
    ```
---
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
---

