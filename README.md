# 🔬 DevOps Sandbox

Welcome to my DevOps engineering sandbox! This repository serves as a practical laboratory for testing infrastructure automation, configuration management, containerization, and modern operational workflows.

## 🛠️ Tech Stack & Tools
* **OS / Virtualization:** CentOS Stream 9, Vagrant, VirtualBox
* **Infrastructure as Code:** (Soon: Ansible, Terraform)
* **Containers & Orchestration:** (Soon: Docker, Kubernetes)

---

## 🚀 Projects & Labs

### 1. Manual Multi-OS Provisioning (CentOS Stream 9 & Ubuntu Jammy)
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




