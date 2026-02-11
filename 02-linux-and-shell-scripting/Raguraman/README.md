# Linux and Shell Scripting - Assignment 1

## Overview
This assignment covers foundational AWS EC2 setup and Linux command-line operations for DevOps.

## Tasks Completed

### Task 1: Create a Security Group (SG) — Required Ports
- Configured security group with necessary inbound/outbound rules
- Opened required ports for SSH and other services

### Task 2: Create SSH Key Pair — ED25519 + PEM
- Generated ED25519 SSH key pair
- Exported in PEM format for compatibility

### Task 3: Launch EC2 Instance (Ubuntu + t2.micro)
- Launched Ubuntu instance with t2.micro instance type
- Connected security group and SSH key pair

### Task 4: Connect to EC2 via SSH
- Successfully established SSH connection to EC2 instance
- Instance IP: `172.31.38.96`

### Task 5: Linux Commands Practice

#### A) System Basics
- Understanding system information and basic Linux concepts

#### B) Navigation & Listing
- Using `cd`, `ls`, and directory traversal commands

#### C) Create Files & Directories
```bash
mkdir devops-lab
cd devops-lab
mkdir -p projects/app/logs
mkdir day1 day2 day3
touch file1.txt file2.txt notes.md
echo "hello devops" > file1.txt
echo "line2" >> file1.txt
cp file1.txt file1-copy.txt
mv file2.txt renamed-file2.txt
rm renamed-file2.txt
rmdir day3
