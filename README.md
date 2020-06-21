# sys_info.py

This Script will find simple information of the local operating system like:
- General Information
- Boot Time
- CPU information
- number of cores
- CPU frequencies
- CPU usage
- Memory Information
- Memory Details
- Disk Information
- Disk Partitions
- IO statistics since boot
- Network information
- Network interfaces

## Installation

git clone into this repository & Setup the Required libraries - 

```bash
git clone https://github.com/idanbuller/System-Info-s.git
```

## Usage + Demo

```bash
python3 sys_info.py


======================================== System Information ========================================
System: Windows
Node Name: laptop
Release: 10
Version: 10.0.17763
Machine: AMD64
Processor: Intel64 Family 6 Model 142 Stepping 10, GenuineIntel
======================================== Boot Time ========================================
Boot Time: 
======================================== CPU Info ========================================
Physical cores: 4
Total cores: 8
Max Frequency: 2112.00Mhz
Min Frequency: 0.00Mhz
Current Frequency: 1910.00Mhz
CPU Usage Per Core:
Core 0: 24.3%
Core 1: 21.5%
Core 2: 15.6%
Core 3: 10.9%
Core 4: 12.5%
Core 5: 9.2%
Core 6: 17.2%
Core 7: 7.8%
Total CPU Usage: 15.0%
======================================== Memory Information ========================================
Total: 15.86GB
Available: 3.19GB
Used: 12.67GB
Percentage: 79.9%
==================== SWAP ====================
Total: 27.86GB
Free: 10.09GB
Used: 17.78GB
Percentage: 63.8%
======================================== Disk Information ========================================
Partitions and Usage:
=== Device: C:\ ===
  Mountpoint: C:\
  File system type: NTFS
  Total Size: 952.53GB
  Used: 688.34GB
  Free: 264.18GB
  Percentage: 72.3%
Total read: 13.64GB
Total write: 28.17GB
======================================== Network Information ========================================
=== Interface: Ethernet ===
=== Interface: Ethernet ===
  IP Address: 169.254.165.44
  Netmask: 255.255.0.0
  Broadcast IP: None
```

# wifi_passwords.py

CISO: I will sign in to the LAN for you, but i won't give you password in clear text.  
ME: hahaha! OK!

```bash
python3 wifi_passwords.py

HMB1xx                        |  ZZZZZZZZZ
HMB-xx                        |  YYYYYYYYY
FXXDMILL_PUBLIC_Office        |  XXXXXXXXX
```
