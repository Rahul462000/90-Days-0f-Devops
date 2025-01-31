---
title: "Networking : Complete Guide for DevOps"
seoTitle: "networking"
datePublished: Fri Jan 31 2025 17:34:44 GMT+0000 (Coordinated Universal Time)
cuid: cm6l1nthr000709k07u9r7iwx
slug: networking-complete-guide-for-devops
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1738344830974/f0bc073f-f679-4498-9625-7b3dbaf9a3a2.jpeg

---

# Basics of networking in DevOps

Networking is the backbone of modern IT infrastructure, and understanding networking models like OSI and TCP/IP models is crucial for DevOps. Additionally, knowledge of essential protocols and their respective ports is necessary for:-

* Managing cloud infrastructure ⛈️
    
* Deploying applications 🚀
    
* Ensuring Security 🔐
    

## 1️⃣ Importance of Networking in DevOps 🔥

Just imagine you have ordered food from online platforms like Zomato or Uber Eats, the process goes like Selecting a Dish🍕 ——&gt; place and order💵 ——&gt; restaurant receives a request ——&gt;once prepared delivery person delivers at your doorstep 🏠

now networking works in the same manner :

* Your computer is **Customer** sends a request.
    
* The Server is the **restaurant** processes it.
    
* The network is Delivery system that ensures a smooth and secure delivery.
    

In another simple language, Networking Allows computers🖥️, Servers, and applications to communicate efficiently over the Internet or within an organization🏢

## 2️⃣Types of Network:——&gt;

1. WAN: wide area network.
    
2. MAN: metropolitan area network.
    
3. LAN: local area network.
    
4. PAN: personal area network.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1738330889901/96d27b1e-1637-4507-b1bb-91c0ffbfcd41.png align="left")

## 3️⃣ OSI Model (Open Systems Intercommunication Model)

It is a set of instructions and procedures through which different computer systems communicate over a network.

⚒️ OSI Model - 7 Layers (Bottom to Top)

### 1️⃣ **Physical layer**⚡

* Deals with hardware and different connections (cables, Wi-Fi)
    

Example: Ethernet, USB.

### 2️⃣**Data link layer**📝

* Manages Data transfer between devices on the **same network**
    
    Example: MAC address, Switches.
    

### 3️⃣ **Network Layer** 🌐

* Manages/Decide the best path for the data & IP address
    
    Example: Router, IP addresses.
    

### 4️⃣**Transport Layer**🚌

* Ensures error-free and uninterrupted data delivery (TCP & UDP)
    
    Example: TCP (for reliability), UDP(for speed).
    

### **5️⃣Session Layer⚒️**

* Maintains & Manages communication sessions between devices.
    
    Example: Logins, API sessions.
    

### **6️⃣Presentation Layer🎨**

* To Translate, encrypt, and compress data
    
    Examples are JPEG, MP4, and SSL encryption.
    

### **7️⃣Application Layer🧑‍💻**

* The interface for User (websites, emails, applications)
    
    Example: HTTP, FTP, Email ( SMTP, IMAP, POP3)
    

## 4️⃣TCP/IP Model (Transmission Control Protocol / Internet Protocol)

### TCP/IP Model - 4 Layers

1️⃣ **Network Access Layer** 🔌

* Equivalent to **Physical + Data Link** layers of OSI
    
* Deals with actual hardware & Transmission
    

2️⃣ **Internet Layer** 🌍

* Equivalent to the **Network Layer** in OSI
    
* Uses IP addresses for routing (Router, IP Address, ICMP)
    

3️⃣ **Transport Layer** 🚛

* Equivalent to the **Transport Layer** in OSI
    
* Handles TCP & UDP for reliable/unreliable transmission
    

4️⃣ **Application Layer** 🌐

* Equivalent to **Session + Presentation + Application** layers in OSI
    
* Directly interacts with users (Browsers, Emails, Apps)
    

![Tcp Ip Model With Diagram Tcp/ip Network Model. An Image Of](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Flearnlearn.uk%2Falevelcs%2Fwp-content%2Fuploads%2Fsites%2F20%2F2020%2F06%2FOSI-to-TCPIP-Model.png&f=1&nofb=1&ipt=de99d64b62fd1debba5d27c7cccdabf81907bbaee948c8fc24c50a94f55fbf19&ipo=images align="center")

| **Feature** | **OSI Model** | **TCP/IP Model** |
| --- | --- | --- |
| Layers | 7 Layers | 4 Layers |
| Usage | Theoretical | Practical |
| complexity | more | simple |
| Developed By | ISO | Dod |
| Structure | Clear Specific | Merges Some OSI Layers |

# IP Adress

⭐IP address means Internet Protocol Address it is a unique identifier assigned to a device in a network to enable communication.

⭐In **DevOps**, IP addresses are crucial for managing infrastructure, networking, automation, and cloud deployments.

# 🌐 **Subnetting Explained Simply**

## 🔹 **What is Subnetting?**

**Subnetting** is the process of dividing a **large network** into **smaller, more manageable subnetworks (subnets)**. It helps **optimize IP address usage, improve security, and enhance network performance**.

## 🏗 **Why is Subnetting Important?**

✅ **Efficient IP Usage** – Prevents wastage of IP addresses  
✅ **Better Security** – Isolates networks to limit access  
✅ **Improved Performance** – Reduces network congestion  
✅ **Simplifies Management** – Organizes large networks into smaller sections

# 🌐 **Important Protocols & Ports for DevOps**

## 🔹 **Networking Protocols & Ports**

1️⃣ **HTTP (HyperText Transfer Protocol)** 🌍

* **Port:** `80`
    
* Used for **web communication** (non-secure websites)
    

2️⃣ **HTTPS (HTTP Secure)** 🔒

* **Port:** `443`
    
* Secure version of HTTP using **SSL/TLS encryption**
    

3️⃣ **FTP (File Transfer Protocol)** 📂

* **Ports:** `20` (Data), `21` (Control)
    
* Used for **file transfers** between servers
    

4️⃣ **SFTP (Secure File Transfer Protocol)** 🔐

* **Port:** `22`
    
* A secure version of FTP runs over **SSH**
    

5️⃣ **SSH (Secure Shell)** 🔑

* **Port:** `22`
    
* Used for **remote server access** and secure communication
    

6️⃣ **Telnet** 🖥

* **Port:** `23`
    
* Used for remote login (Insecure, replaced by SSH)
    

7️⃣ **DNS (Domain Name System)** 🌎

* **Port:** `53`
    
* Resolves domain names to IP addresses
    

8️⃣ **DHCP (Dynamic Host Configuration Protocol)** 🏠

* **Ports:** `67` (Server), `68` (Client)
    
* Assigns **IP addresses dynamically** to devices
    

9️⃣ **SMTP (Simple Mail Transfer Protocol)** 📧

* **Port:** `25` (Default), `465` (SSL), `587` (TLS)
    
* Used for **sending emails**
    

🔟 **POP3 (Post Office Protocol v3)** 📥

* **Port:** `110` (Default), `995` (SSL)
    
* Used for **retrieving emails from the server**
    

1️⃣1️⃣ **IMAP (Internet Message Access Protocol)** 📬

* **Port:** `143` (Default), `993` (SSL)
    
* Used for **accessing emails from the server**
    

> **Protocols like SSH, HTTP, HTTPS, DNS, and FTP** are essential for DevOps