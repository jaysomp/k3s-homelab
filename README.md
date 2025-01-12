
# Homelab Setup

This repository contains the setup and configuration for my 3-node k3s Kubernetes cluster, designed for gaining hands-on experience with Kubernetes and migrating my existing services from a previous homelab setup.

## Homelab Architecture

The homelab consists of 3 nodes running **Fedora Server** with **k3s** for lightweight Kubernetes deployment:

### 1. **Control Plane Node**  
- **CPU**: Intel Core i7-6700 (8 cores) @ 4.00 GHz  
- **GPU**: NVIDIA GeForce GTX 750 Ti (Discrete)  
- **Memory**: 16GB

### 2. **Worker1 Node**  
- **CPU**: Intel Core i5-2430M (4 cores) @ 3.00 GHz  
- **GPU**: Intel 2nd Generation Core Processor (Integrated)  
- **Memory**: 4GB

### 3. **Worker2 Node**  
- **CPU**: Intel Core 2 Duo P7550 (2 cores) @ 2.26 GHz  
- **GPU**: NVIDIA GeForce 9400M (Discrete)  
- **Memory**: 2GB

## Purpose

This homelab is primarily intended to:
- Gain hands-on experience with Kubernetes.
- Migrate existing services running on the previous homelab setup to this new cluster.

### Previous Homelab Setup
The services from my past homelab setup can be found here: [Previous Homelab Setup](https://github.com/jaysomp/homelab).

---
