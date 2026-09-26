# Server Inventory

## Host

joeyserver

## Operating System

Ubuntu 24.04.4 LTS

## Hardware

CPU:
Intel Core i3-4160T
4 cores / 4 threads

Memory:
16GB RAM

## Storage

OS Disk:
235GB SSD

Root filesystem:
Expanded from 100GB to 235GB using LVM.

Media Storage:
- /mnt/joey_storage
- /mnt/joey_backup

## Existing Workloads

Docker:
- Plex
- Jellyfin

## Kubernetes Plan

Deploy a single-node k3s cluster while maintaining existing Docker workloads.

Initial Kubernetes workloads:
- Home dashboard
- Monitoring
- Container management tools
- Future migration candidates:
  - Plex
  - Jellyfin