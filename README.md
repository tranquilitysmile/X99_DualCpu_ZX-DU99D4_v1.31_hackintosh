# X99_DualCpu_ZX-DU99D4_v1.31_hackintosh
Kllisre/Atermiter X99 Dual CPU ZX-DU99D4 v1.31 Hackintosh Sequoia
![telegram-cloud-photo-size-2-5301197491603103813-y](https://github.com/user-attachments/assets/6def324b-7e9a-4dd6-8edf-20d353d4cce1)


## Specification
| **Component** | **Model** |
| ------------- | --------- |
| CPU | Intel Xeon E5 2699 v3 @ 3.6GHz x2 (Unlock Turbo Boost with bios mod) |
| Motherboard | Kllisre/Atermiter X99 Dual CPU ZX-DU99D4 v1.31|
| RAM | 64GB Micron MTA18ASF1G72PZ ECC REG 2133 (8 slots 8 gb) |
| GPU | AsRock RX 6600 XT Phantom Gaming OC 8G  |
| Ethernet | RTL8111H |
| WIFI+BT | Fenvi T919 |
| OS Disk (SATA) | Samsung 980 512 GB NVME SSD |

## Before start

- MacOS have CPU Core limit (64 cores) in my case with x2 Intel Xeon E5 2699 v3, i disable 2 core on both CPU in bios, without it system can't boot
- Don't forget generate and set in config.plist you own MLB/Serial etc 
- You should use exactly same bios settings like in repo BIOS folder, most of problem with booting installer and system in bios settings
- For working WiFi/BT/Airdrop etc...you should use OpenCore Legacy Patcher Developers builds from https://github.com/dortania/OpenCore-Legacy-Patcher
- I use self made bios mod with -50mv undervolting and turbo boost unlock, but it's not necessary to start the system

**macOS version**: 15 beta 4

**OpenCore version**: 1.1

**SMBIOS**:  iMacPro1,1

## Working
- Everything except sleep/wake (can't work on X99 platform with dual cpu)

## Disclaimer

This documentation is published for the sole purpose of learning and tech enthusiasm and with no guarantees of any kind, I’m not responsible of any harm of any kind or loss of data that may occur.
