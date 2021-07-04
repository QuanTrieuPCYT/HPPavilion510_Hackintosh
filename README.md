# HP Hamar Motherboard - macOS High Sierra and Up
OpenCore bootloader (yes, Clover shit) that makes your HP Hamar-powered PC (510-P and 260-P Series) runs macOS High Sierra and up!
## Motherboard Specs:
![image](https://user-images.githubusercontent.com/73286927/124374625-18f14600-dcc7-11eb-8365-b0313750ff68.png)
* HP/Compaq name: Hamar
* SSID: 81B4
* Chipset: Intel H170
* Processor upgrade information: LGA 1151, accept the following CPU upgrades: `G3900T, G4400T, i3-6100T, i5-6400T and i7-6700T`
* iGPU does not work if a graphics card is installed.
* Ethernet: Realtek RTL8161
* Expansion Slots: 1x PCI-E (GEN 3) x16 socket and 1x M.2 socket 1, key A
* 1x HDMI, 2x USB 3.0, 2x USB 2.0 (and another 2x USB 2.0 at the front if HP case is properly installed), 1x VGA (doesn't work in macOS), 1x HDMI, 3x Audio Ports (In, Out and Mic) and 1x Headphone at the front if HP case is properly installed.
## Note:
* The Realtek Wi-Fi card that came with most of these 510-P and 260-P series PCs will not gonna work in macOS, so you'll need another card for wireless functionality (Intel or Broadcom M2 cards)
* Work is still in progress for the SD Card Reader.

**For more detailed info please visit https://support.hp.com/us-en/document/c05066299**
## Tested hardware:
**HP Pavilion Desktop 510-p007l (My main desktop PC)**
* CPU: Intel® Pentium® G4400T (fake ID required)
* RAM: 2x 4GB DDR4 2133MHz
* GPU: GIGABYTE GTX 1050 2GB
* SSD: KingSpec P4-120 120GB SATA SSD (Windows 11)
* HDD: WD Blue WD10EZEX 1TB
* **Runs macOS High Sierra (10.13.6) perfectly (with NVIDIA Web Driver).**

**HP Slimline Desktop - 260-p026 (ENERGY STAR)**
* CPU: Intel® Core™ i3-6100T
* RAM: 2x 8GB DDR4 2133MHz
* GPU: Intel HD Graphics 530 (GT2)
* SSD: Kingston SSDNow V300 120GB SATA SSD
* **Runs macOS Catalina & Big Sur perfectly.**
