# Pre-configured-virtual-machines
Debian-SSH-Lab.ova Kali-AD-Lab.ova Ubuntu-Web-Lab.ova Windows-Server-Lab.ova
# Debian Security Lab

Preconfigured Debian 13 security lab VM for VirtualBox.

## Download

Download the latest `.OVA` from:

Releases → Latest Release

## Requirements

- VirtualBox
- 8 GB RAM recommended
- ~50 GB free disk space

## VM specifications

- Debian 13
- Xfce
- 2 CPU
- 6 GB RAM
- 50 GB virtual disk
- SSH enabled

## Installation

1. Install VirtualBox.
2. Download the `.OVA` from Releases.
3. Open VirtualBox.
4. Select File → Import Appliance.
5. Select the downloaded `.OVA`.
6. Click Import.
7. Start the VM.

## Login

Username: `test`

Password: `123`

Username: `root`

Password: `root`

## Network

Use Host-Only Adapter for the security lab.

## Warning

This VM contains intentionally configured security-lab services.
Use it only in an isolated lab environment.
Do not expose vulnerable services directly to the Internet.
