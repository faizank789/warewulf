<p align="center">
  <img src="https://github.com/faizank789/warewulf/blob/e524a22b89ff6451b9ebf4bce58cee6087ecdc96/images/warewulf.png" alt="warewulf" />
</p>

# What is Warewulf?
Warewulf is an open-source cluster provisioning system used in High-Performance Computing (HPC) environments. It simplifies the process of managing and provisioning compute nodes by using a lightweight, stateless, container-based approach.

# Why do we need Warewulf?

🚀 Automated Provisioning – Quickly deploy multiple nodes with a consistent OS and configuration.
⚙️ Centralized Management – Manage all compute nodes from a single master node.
📦 Container-based Images – Build and customize node images easily using container technology.
🔄 Scalability – Scale out HPC clusters efficiently without complex manual setup.
🖥️ PXE Boot Support – Nodes boot directly from the master using PXE without requiring local disks.

# Our Setup

Master Node: Installed on VMware Workstation
Provisioning: Using PXE boot for compute nodes
Container Image: Based on Rocky Linux 9
HPC Utilities: Installed inside the Warewulf container for compute workloads
Scaling: Additional VMs (nodes) can be created and automatically provisioned via Warewulf profiles


