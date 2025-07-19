# 🛡️ Web Application Firewall (WAF) Lab: Protecting DVWA with SafeLine

---

## 📖 Overview
This project documents my hands-on lab setup for learning **web application security** by:
1. Deploying **Damn Vulnerable Web App (DVWA)** on an Ubuntu server.
2. Simulating attacks (e.g., SQL injection) from Kali Linux.
3. Configuring **SafeLine WAF** to detect and block attacks.
4. Testing advanced WAF features like rate limiting and IP blocking.

**Goal:** Understand how WAFs work in real-world scenarios by building a controlled lab environment.

---

## 🛠️ Lab Setup Guide

### 🔧 **1. Prerequisites**
- **Hardware:**  
  - 8GB+ RAM, 50GB+ disk space.  
- **Software:**  
  - VirtualBox ([Download](https://www.virtualbox.org/wiki/Downloads))  
  - Kali Linux ISO ([Download](https://www.kali.org/get-kali))  
  - Ubuntu Server ISO ([Download](https://ubuntu.com/download/server))  

---

### 🖥️ **2. Virtual Machine Setup**
#### **Step 1: Install VirtualBox**
- Create two VMs:  
  - **Kali Linux** (Attacker)  
  - **Ubuntu Server** (Hosts DVWA + WAF)  

