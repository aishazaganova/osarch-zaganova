# Lab 0 — Inventory your own machine

Driver: Aisha Zaganova
Machine: <Windows32>
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

## What did not work the first time

At least one thing. What I saw, what it turned out to be, what I did about it.

## Evidence

- [evidence/](evidence/) — one line per file on what it proves
