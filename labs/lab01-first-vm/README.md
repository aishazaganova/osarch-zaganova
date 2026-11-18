# Lab 1 — Your first virtual machine

Driver: Aisha Zaganova
Machine: host: Windows 11, guest: Linux
Date: 18.10.2026

## What I did
```
1. Installed VMware-Workstation-Full-26H1u1-25688693. Licence: https://knowledge.broadcom.com/external/article/368667/download-and-license-vmware-desktop-hype.html
2. Created VM lab01-ubuntu: 2vCPU, 2 GB RAM, 20 GB dynamic disk, NAT.
3. Installed Ubuntu Server, took snapshot 'clean-install'.
4. First, looked first at:
<cat /etc/hostname>
Then broke it:
<sudo rm /etc/hostname>

<sudo reboot>
And then, confirmed it:
<cat /etc/hostname>
<hostnamect1>
5. Rolled back to 'clean-install':
<cat /etc/hostname>
printed <lab01>
```
## Resource justification
My host has 16 threads, 8 GB of RAM and 512 GB free on the VM volume.
Idle, the host already uses about 13 GB of RAM.
I gave the guest 2 vCPUs of my 16 threads because it was a comfortable start and the space is still left for future reserves.
I gave it 2 GB of my 8 GB RAM because 2.2 GB is used by my host and I keep 3.8 GB for other guests.
I gave it a 20 GB dynamically allocated disk of my 512 GB free because it allowed enough free space for other VMs in my laptop.

## Result
The VM boots up and the break-and-rollback cycle is shown in the evidence bellow.

## What did not work the first time
Sometimes I got quite confused in the steps and commands, so I carefully read the brief 2-3+ times to ensure the correctness of my actions/commands.

## Evidence

- [evidence/](evidence/vm-settings.png) — CPU, memory, disk as configured
- [evidence/](evidence/guest-release.txt) — output of lsb_release -a inside the guest
- [evidence/](evidence/broken.png) — the guest in its broken state
- [evidence/](evidence/snapshot-list.png) — snapshots, after the rollback
