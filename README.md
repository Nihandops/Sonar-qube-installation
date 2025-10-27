# Sonar-qube-installation

# SonarQube Installation Guide on Linux

This guide provides step-by-step instructions to install SonarQube on a Linux server with PostgreSQL database.

## Prerequisites
- Linux server (CentOS/RHEL 7+)
- sudo privileges
- Internet connection

## Installation Steps

### 1: Update and Install Dependencies

```bash
sudo yum update -y
sudo yum install wget unzip -y
sudo yum install java-11-openjdk-devel -y
