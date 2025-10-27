# Sonar-qube-installation

# SonarQube Installation Guide on Linux

This guide provides step-by-step instructions to install SonarQube on a Linux server with PostgreSQL database.

## Prerequisites
- Linux server (CentOS/RHEL 7+)
- sudo privileges
- Internet connection

## Installation Steps

###  Update and Install Dependencies

```bash
sudo yum update -y
sudo yum install wget unzip -y
sudo yum install java-11-openjdk-devel -y


**Follow these steps in exact order for successful installation:**

### 🔰 **STEP 1: Start Here**
**File:** `Install and Setup PostgreSQL 14 Database.md`
- PostgreSQL 14 Installation
- Database Configuration
- User & Privileges Setup

### 👤 **STEP 2: User Configuration**  
**File:** `Create User for SonarQube.md`
- Create 'sonar' System User
- Set Permissions & Ownership

### 📦 **STEP 3: SonarQube Installation**
**File:** `Download and Install SonarQube.md`
- Download SonarQube Binaries
- Extract & Directory Setup

### ⚙️ **STEP 4: Configuration**
**File:** `Configure SonarQube.md`
- Database Connection Settings
- Environment Configuration
- Security Settings

### 🔄 **STEP 5: Service Setup**
**File:** `Configure Systemd Service.md`
- Systemd Service Creation
- Auto-start Configuration
- Service Management

### 🌐 **STEP 6: Access & Verification**
**File:** `Access SonarQube.md`
- Service Startup
- Web Interface Access
- Login & Verification

