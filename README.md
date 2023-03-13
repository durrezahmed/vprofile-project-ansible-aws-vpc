# DevOps Project - VPC Setup for Vprofile Project on AWS Cloud using Ansible for Cloud Automation

This is a DevOps project for [VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html) (_Virtual Private Cloud_) Setup for Vprofile Project on AWS Cloud using [Ansible](https://www.ansible.com/) for Cloud Automation.

[Link](https://github.com/durrezahmed/vprofile-project-devops) for vprofile app repository.

## Scenario - Current Situation:

- AWS Cloud Management Team

- Deploy / Setup Infrastructure on Cloud

- Usage of Secure and HA (Highly Available) VPC for New Projects

- Regular Requests

## Problem - Issues with Current Situation:

- VPC Consists of Many Moving Parts

- Subnets, NAT Gateways, Internet Gateways, Route Tables, NACLs, Security Groups

- Bastion Hosts

- Human Error can lead to Non Functional or Exposed VPC

- Managing Manually is a Time Consuming Task

## Solution - Fix:

- Configuration Management of VPC

- Automatic Setup (No Human Errors)

- Centralize Change Management

- Version Control (IaC)

## Tools used in the Project:

- [**Ansible**](https://www.ansible.com/) - Configuration Management of VPC

- [**AWS Cloud Platform**](https://aws.amazon.com/) - VPC Setup with Bastion Hosts

## Usage (Flow of Execution):

1. Login to AWS - [Link](https://aws.amazon.com/marketplace/management/signin) to Login to your AWS Account.

2. Create `EC2 Instance` to Run Ansible Playbooks

3. Install `Ansible`

4. Install Boto

5. Setup `EC2 Role` for Ansible

6. Create a Project Directory

7. Create Variables File for `VPC` and `Bastion Host`

8. Create `VPC Setup` Playbook

9. Create `Bastion Setup` Playbook

10. `site.yaml` Playbook to call both Playbooks at once
