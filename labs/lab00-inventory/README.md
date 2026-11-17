# Lab 0 — Inventory your own machine

Driver: Aisha Zaganova
Machine: Lenovo Windows 11
Date: 11.10.2026

## What I did
```
<Get-CimInstance Win32_Processor | Format-List *>
<Name                                    : AMD Ryzen 7 5825U with Radeon
                                          Graphics
NumberOfCores                            : 8
NumberOfLogicalProcessors                : 16>

<Get-CimInstance Win32_PhysicalMemory>
<Capacity             : 8589934592
Speed                 : 3200>

<systeminfo>
<Total Physical Memory:         5 981 MB>

<Get-PhysicalDisk | Format-List *>
<FriendlyName                     : Micron MTFDKCD512QGN-1BN1AABLA
MediaType                         : SSD
BusType                           : NVMe>
```

## Result
The CPU model: AMD Ryzen 7 5825U with Radeon Graphics
Core count: 8
Thread count: 16
Total memory: 5 981 MB
Number of installed modules: 37
Speed: 3200
Disk model: Micron MTFDKCD512QGN-1BN1AABLA
Media type: SSD
BusType: NVMe

## What did not work the first time

I struggled with finding how to do this whole github thing and asked my friends to help me, so here I am a month later submitting lab00

## Evidence

- [evidence/](evidence/cpu.txt) — the CPU model, core count and thread count. 
- [evidence/](evidence/memory.txt) — the total memory, the number of installed modules and their speed.
- [evidence/](evidence/disk.txt) — the disk model, its type (HDD, SATA SSD, NVMe) and the free space on the volume I will store VMs on.
