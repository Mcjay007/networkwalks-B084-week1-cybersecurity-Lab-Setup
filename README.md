# networkwalks-B084-week1-cybersecurity-Lab-Setup

# 🔐 CYBERSECURITY LAB ENVIRONMENT SETUP

### Building a Virtual Cybersecurity Lab Using Kali Linux and Oracle VirtualBox

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red)
![Kali Linux](https://img.shields.io/badge/OS-Kali%20Linux-blue)
![VirtualBox](https://img.shields.io/badge/Hypervisor-VirtualBox-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 PROJECT OVERVIEW

This project documents the successful setup and configuration of a virtual cybersecurity laboratory using **Kali Linux and Oracle VirtualBox**.

The primary objective was to establish a functional virtual environment for hands-on cybersecurity training, networking exercises, ethical hacking, and penetration testing practice.

During this setup, I configured a NAT Network, assigned a static IP address to Kali Linux, verified network connectivity and DNS resolution, and created a clean Virtual Machine (VM) snapshot.

This laboratory provides a controlled environment for future cybersecurity experiments and practical exercises.

---

## 🎯 PROJECT OBJECTIVES

The major objectives of this project were to:

- Configure a NAT Network in Oracle VirtualBox.
- Set up Kali Linux as a virtual machine.
- Assign a static IP address to Kali Linux.
- Establish reliable network connectivity.
- Verify DNS resolution.
- Test communication between the virtual machine and network gateway.
- Create a clean VM snapshot for system recovery.
- Prepare the lab environment for future cybersecurity activities.

---

## 🛠️ TOOLS AND TECHNOLOGIES

| Tool | Purpose |
|---|---|
| Oracle VirtualBox | Virtualization platform |
| Kali Linux | Cybersecurity operating system |
| NAT Network | Virtual network configuration |
| Linux Terminal | Network configuration and testing |
| VirtualBox Snapshot | Backup and recovery point |

---

## ⚙️ LAB ENVIRONMENT CONFIGURATION

| Component | Configuration |
|---|---|
| Host Operating System | [Your Host OS] |
| Hypervisor | Oracle VirtualBox |
| Guest Operating System | Kali Linux |
| Network Mode | NAT Network |
| IP Configuration | Static IPv4 |
| Network Connectivity | Verified |
| DNS Resolution | Verified |
| VM Snapshot | Created |

**Note:** Replace bracketed values with your actual system specifications and network configuration.

---

## 🏗️ KEY TASKS COMPLETED

### 1. NAT Network Configuration

Configured a NAT Network within Oracle VirtualBox to provide network connectivity to the Kali Linux virtual machine.

This configuration allows virtual machines connected to the same NAT Network to communicate with each other while accessing external networks through Network Address Translation.

**Outcome:**
- NAT Network successfully configured.
- Kali Linux network adapter connected to the NAT Network.
- Virtual network prepared for future lab exercises.

### 2. Static IP Address Configuration

Configured a static IPv4 address for the Kali Linux virtual machine to ensure consistent network identification.

The configuration included:

- IP Address: [Your Static IP]
- Subnet Mask: [Your Subnet Mask]
- Default Gateway: [Your Gateway]
- DNS Server: [Your DNS Server]

**Outcome:**

Successfully assigned a static IP address to Kali Linux for consistent network communication.

### 3. Network Connectivity and DNS Verification

Performed network connectivity tests to confirm that Kali Linux could communicate with the configured network gateway and access external network resources.

**Commands used for verification:**

```bash
# Display network interface information
ip addr

# Display routing information
ip route

# Test gateway connectivity
ping -c 4 <gateway-ip>

# Test internet connectivity
ping -c 4 8.8.8.8

# Test DNS resolution
nslookup google.com
```

**Outcome:**
- Network interface configuration checked.
- Network connectivity verified.
- DNS resolution successfully verified.

### 4. Clean Virtual Machine Snapshot

Created a clean VM snapshot after completing the initial network configuration.

The snapshot serves as a recovery point that allows the Kali Linux environment to be restored to its original configured state whenever necessary.

**Snapshot Name:**
`Kali-Linux-Clean-Baseline-Week-1`

**Outcome:**
- Clean VM snapshot successfully created.
- Baseline environment preserved.
- Recovery point established for future practical exercises.

---

## 🔍 VERIFICATION SUMMARY

| Task | Verification | Status |
|---|---|---|
| NAT Network Configuration | VirtualBox network settings | Completed |
| Static IP Configuration | `ip addr` | Completed |
| Gateway Connectivity | `ping <gateway-ip>` | Verified |
| Internet Connectivity | `ping 8.8.8.8` | Verified |
| DNS Resolution | `nslookup google.com` | Verified |
| VM Snapshot | VirtualBox Snapshot Manager | Created |

---

## 📚 WHAT I LEARNED

Through this practical exercise, I gained hands-on experience in:

1. Understanding virtual network configuration using Oracle VirtualBox.
2. Configuring NAT Networks for virtual machines.
3. Assigning static IP addresses in Kali Linux.
4. Understanding IP addressing, gateways, and DNS.
5. Troubleshooting and verifying network connectivity.
6. Creating and managing virtual machine snapshots.
7. Building a controlled environment for cybersecurity practice.

---

## 🔐 SECURITY AND ETHICAL CONSIDERATIONS

This laboratory is designed strictly for educational purposes and authorized cybersecurity testing.

All future vulnerability assessments, network scans, and penetration testing activities will be conducted only against systems that I own or have explicit permission to test.

---

## 🚀 NEXT STEPS

Having completed the initial lab setup, the next phase of my cybersecurity learning journey will focus on:

- Network reconnaissance.
- Network scanning using Nmap.
- Understanding open ports and services.
- Basic vulnerability assessment.
- Packet analysis using Wireshark.
- Exploring cybersecurity tools available in Kali Linux.

---

## 📸 PROJECT SCREENSHOTS

Screenshots documenting the lab configuration and successful completion of the setup will be included below.

Suggested screenshot structure:

```text
Cybersecurity-Lab-Setup/
│
├── README.md
│
└── screenshots/
    ├── 01-virtualbox-nat-network.png
    ├── 02-kali-linux-desktop.png
    ├── 03-static-ip-configuration.png
    ├── 04-network-connectivity-test.png
    ├── 05-dns-verification.png
    └── 06-clean-vm-snapshot.png
```

Add your screenshots using the following Markdown format:

![NAT Network Configuration](screenshots/01-virtualbox-nat-network.png)

![Kali Linux Desktop](screenshots/02-kali-linux-desktop.png)

![Static IP Configuration](screenshots/03-static-ip-configuration.png)

![Network Connectivity Test](screenshots/04-network-connectivity-test.png)

![DNS Verification](screenshots/05-dns-verification.png)

![Clean VM Snapshot](screenshots/06-clean-vm-snapshot.png)

---

## 🔗 TOOLS AND RESOURCES

- Kali Linux: https://www.kali.org/get-kali/
- Oracle VirtualBox: https://www.virtualbox.org/wiki/Downloads
- Kali Linux Documentation: https://www.kali.org/docs/
- VirtualBox User Manual: https://www.virtualbox.org/manual/

---

## 👨‍💻 AUTHOR

**Mojetoluwa Ojo**

Cybersecurity Learner | Aspiring Cybersecurity Analyst

I am building practical cybersecurity skills through hands-on laboratory exercises, networking configuration, security tools, and continuous learning.

**GitHub:** [https://github.com/Mcjay007/networkwalks-B084-week1-cybersecurity-Lab-Setup/edit/main/README.md)]

**LinkedIn:** [https://www.linkedin.com/in/ojo-mojetoluwa-87369469]

---

## 📌 PROJECT INFORMATION

| Item | Details |
|---|---|
| Project | Cybersecurity Lab Setup |
| Week | Week 1 |
| Platform | Oracle VirtualBox |
| Operating System | Kali Linux |
| Focus Area | Virtual Networking and Lab Configuration |
| Project Status | Successfully Completed |

---

⭐ If you find this project useful, feel free to explore and follow my cybersecurity learning journey.

**#Cybersecurity #KaliLinux #VirtualBox #Networking #EthicalHacking #CybersecurityLab #LearningByDoing**
