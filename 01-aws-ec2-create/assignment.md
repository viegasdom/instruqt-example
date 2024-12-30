---
slug: aws-ec2-create
id: t7ypx3yx3dnk
type: challenge
title: Create an AWS EC2 instance
teaser: Every cloud starts from VM
notes:
- type: text
  contents: |-
    You're about to create an EC2 instance using AWS CLI.

    Please wait while we provision the AWS account.
tabs:
- id: 1fiidwz3api4
  title: Cloud CLI
  type: terminal
  hostname: cloud-client
- id: fhjm0h2cmyfx
  title: AWS Console
  type: service
  hostname: cloud-client
  path: /
  port: 80
difficulty: basic
timelimit: 600
lab_config:
  default_layout_sidebar_size: 0
---

👋 Introduction
===============

Use the terminal to create EC2 instance:

```
aws ec2 run-instances --image-id ami-01685d240b8fbbfeb --instance-type t2.nano
```

To complete this challenge, press **Check**.
