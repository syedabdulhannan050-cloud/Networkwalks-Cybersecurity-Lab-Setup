# Cybersecurity Lab Environment Setup
### Building a Virtual Lab for Cybersecurity Practice

## 📌 Project Overview

This project focuses on setting up a virtual cybersecurity lab using Oracle VirtualBox and Kali Linux. The environment is designed for learning network security, reconnaissance, vulnerability assessment, and ethical hacking in a controlled lab.

## 🎯 Objectives

- Install and configure VirtualBox.
- Set up Kali Linux as a virtual machine.
- Configure a NAT Network.
- Enable clipboard sharing and drag-and-drop.
- Configure a shared folder between Windows and Kali Linux.
- Create a VM snapshot for recovery.
- Document the setup with screenshots.

## 🛠️ Tools Used

| Component | Configuration |
|---|---|
| Host OS | Windows |
| Hypervisor | Oracle VirtualBox |
| Security OS | Kali Linux |
| Network Type | NAT Network |
| Network Prefix | `10.0.0.0/24` |
| Shared Folder | `/downloads` |

## 🪜 Lab Setup Procedure

### Step 1: Install VirtualBox
Installed Oracle VirtualBox to create and manage virtual machines.

### Step 2: Configure the NAT Network
Created a NAT Network in VirtualBox using the `10.0.0.0/24` network prefix.

### Step 3: Set Up Kali Linux
Imported and configured the Kali Linux virtual machine in VirtualBox.

### Step 4: Configure VM Features
Enabled bidirectional shared clipboard and drag-and-drop. Configured a shared folder to transfer files between the host and virtual machine.

### Step 5: Create a Snapshot
Created a VM snapshot to provide a recovery point before future cybersecurity exercises.

## 📸 Screenshots

Screenshots documenting the VirtualBox configuration, Kali Linux environment, shared folder, and snapshot are included in this repository.

## 💡 What I Learned

- Virtual machine setup and configuration.
- Basic virtual networking concepts.
- File sharing between host and guest systems.
- The importance of VM snapshots and documentation.
- Preparing a virtual environment for cybersecurity practice.

## 🔐 Security and Ethical Use

This lab is intended for educational purposes and authorized security testing only. Testing should be performed only on systems you own or have explicit permission to assess.
