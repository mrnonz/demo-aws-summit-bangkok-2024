# Amazon EKS Pod Identity Demo

In this walkthrough, we will demonstrate how to use the new Amazon EKS Pod Identity feature to securely provide AWS access to kubernetes pods.

## Solution Architecture

![Solution Architecture](eks-pod-identity-arch.jpg)

## Pre-requisites

* An AWS Account
* export AWS_REGION=ap-southeast-1 # Replace with your AWS region
* export CLUSTER_NAME=eks-pod-identity-demo # Replace with your cluster name
* export AWS_ACCOUNT=123456789012 # Your AWS Account number
* [AWS CLI](https://aws.amazon.com/cli/) and credentails from both AWS Accounts, alternatively use [AWS CloudShell](https://docs.aws.amazon.com/cloudshell/latest/userguide/welcome.html#how-to-get-started)
* [eksctl](https://eksctl.io/) - a simple CLI tool for creating and managing Amazon EKS clusters
* [git](https://github.com/git-guides/install-git)
  ```shell
    git clone https://github.com/mrnonz/demo-aws-summit-bangkok-2024
    cd demo-aws-summit-bangkok-2024/eks-pod-identity
  ```

## Setup
