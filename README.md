# Kubernetes Homelab 

This repository contains my self-hosted Kubernetes homelab, which I use to learn, experiment, and practice real-world DevOps and SRE concepts.

I work with Kubernetes and cloud infrastructure professionally, and this homelab helps me understand the full lifecycle of running applications from deployment and secrets to monitoring, upgrades, and day-to-day operations.
Everything here is built and managed using a GitOps approach.


# Hardware Specs

This lab runs on bare-metal hardware, not virtual machines.

- Device: Raspberry Pi 5

- Architecture: ARM64 (aarch64)

- RAM: 4 GB

- Storage: 64 GB USB 3.0 SSD

- Network: Wired Ethernet

- Power: Dedicated power supply

The setup is intentionally lightweight but realistic.
Additional nodes can be added later to form a multi-node cluster.

# Software

- Operating System: Raspberry Pi OS (Debian-based) / Ubuntu Server (ARM64)

- Container Runtime: containerd

- Kubernetes Distribution: k3s

- Init System: systemd

- Filesystem: ext4


# Future Improvements

Multi-node cluster

GitOps with Argo CD

Persistent storage with Longhorn

Backup & restore strategy

Network policies

CI integration






