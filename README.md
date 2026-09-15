<img width="997" height="745" alt="Screenshot 2026-09-15 093416" src="https://github.com/user-attachments/assets/57f3c1ad-6309-4861-8cea-25c1648f502c" />
# 🔬 DevOps Sandbox

Welcome to my DevOps engineering sandbox! This repository serves as a practical laboratory for testing infrastructure automation, configuration management, containerization, and modern operational workflows.

## 🛠️ Tech Stack & Tools
* **OS / Virtualization:** CentOS Stream 9, Ubuntu Jammy, Vagrant, VirtualBox
* **Shell & Terminal:** Git Bash, Bash Scripting

---

## 🚀 Projects & Labs

### Lab 1: Manual Multi-OS Provisioning (CentOS Stream 9 & Ubuntu Jammy)
A foundational laboratory focused on deployment, networking, and system administration across different Linux distributions. This lab contrasts Red Hat (CentOS) and Debian (Ubuntu) architectures.

* **Hypervisor:** VirtualBox
* **Deployments:** CentOS Stream 9 & Ubuntu 22.04 LTS (Jammy Jellyfish)
* **Key Tasks:** Comparative package management (`dnf` vs `apt`), static IP configuration, and secure SSH access.

#### 📝 Lab Steps & Completed Objectives:
1. **OS Installation:** Deployed CentOS Stream 9 and Ubuntu 22.04 LTS environments using minimal ISO images.
2. **Network Setup:** Configured host-only and NAT adapters to enable internal communication between nodes while maintaining internet access.
3. **Package Management:** Explored syntax differences for system updates:
   * CentOS: `sudo dnf update -y`
   * Ubuntu: `sudo apt update && sudo apt upgrade -y`
   * Installed foundational tools: `curl`, `net-tools`, `vim`, and `openssh-server`.
4. **Environment Cleanup:** Manually decommissioned and de-allocated virtual hardware resources after successful verification to practice proper lifecycle management.

---

### Lab 2: Automated Multi-OS Provisioning via Git Bash & Vagrant
Transitioned from manual installation to **Infrastructure as Code (IaC)**. This lab automates the creation and configuration of the same CentOS Stream 9 and Ubuntu Jammy environments directly from the terminal.

* **Tools Used:** Git Bash, Vagrant, VirtualBox Hypervisor
* **Automation Level:** Fully automated provisioning
* **Status:** Operational and active

#### 📸 Infrastructure Verification (Lab 2):

##### Active Virtual Machines in VirtualBox:
<img width="1242" height="805" alt="Screenshot 2026-09-15 013555" src="https://github.com/user-attachments/assets/15be7b15-7c5e-46ec-8478-be7f576cd9b4" />


##### SSH Access via Git Bash Terminal:
<img width="1477" height="761" alt="Screenshot 2026-09-15 013619" src="https://github.com/user-attachments/assets/281cc646-f71d-452e-99ce-50372d17c050" />

