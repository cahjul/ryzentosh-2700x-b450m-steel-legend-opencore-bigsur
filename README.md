## AMD Ryzen Hackintosh Big Sur 11.x.x - Opencore EFI for Asrock B450M Steel Legend
## This EFI only tested on Big Sur 11.7.1

## Specification
| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 7 2700X 3.7 GHz Eight-Core AM4 Processor |
| Motherboard | Asrock B450M Steel Legend AM4 Motherboard DDR4 |
| RAM | 32GB (2 x 16GB) Adata DDR4 RAM @ 2600Mhz CL 19-19-19 |
| Audio Chipset | Realtek ALC892 |
| GPU | Sapphire NITRO+ RX 580 Special Edition @ 8GB GDDR5  |
| Ethernet | Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter) |
| OS Disk (NVME/SATA) | Crucial P2 1TB NVMe PCIe M.2 SSD | WD Blue 1TB 3.5 inch 7200RPM |

**macOS version**: Big Sur 11.7.1 (Can be use for 11.x.x++ also)  

**OpenCore version**: 0.8.6

**SMBIOS**:  MacPro7,1

## How to use
  1. Create directory "EFI" in your EFI partition (e.g. pendrive or hard drive)
  2. Clone this repo and paste directiories "BOOT" and "OC" onto created directory
  3. Download [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) to generate unique SMBIOS information. Run it and select **Generate SMBIOS**, as model select **iMacPro7,1**.
  4. Boot it!  

## Disclaimer

This documentation is published for the sole purpose of learning and tech enthusiasm and with no guarantees of any kind, I’m not responsible of any harm of any kind or loss of data that may occur.

## Credits to
## OpenCore Related Team
## wildtigon - for the beautiful README.md
## Others that not mentioned
