# Lab-Week-7
# Intro to Ansible Lab – Automating Nginx Deployment on AWS

The lab uses Terraform to create two EC2 instances and Ansible to configure Nginx automatically on both.  

---

##  1. Create a New SSH Key Pair

```bash
# Generate a new Ed25519 SSH key named "aws"
ssh-keygen -t ed25519 -f ~/.ssh/aws -C "ansible-lab-aws"
