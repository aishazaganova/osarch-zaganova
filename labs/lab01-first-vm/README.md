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
My host has
## Result

## What did not work the first time

At least one thing. What I saw, what it turned out to be, what I did about it.

## Evidence

- [evidence/](evidence/) — one line per file on what it proves
