---
{"dg-publish":true,"dg-permalink":"linux/onintelmac/","permalink":"/linux/onintelmac/","dg-note-properties":{}}
---

My recommended setup for running Linux on Intel Mac hardware.

- Distro: [[Linux/Linux Mint\|Linux Mint]], because it has the best support for Broadcom WiFi drivers AND for locking to the LTS version of the Linux Kernel to prevent breakages with that driver
	- Version: 22.1 (starts on Linux Kernel 6.8, which supports Broadcom)
- Desktop environment: Cinnamon, because it is the most modern and has the easiest pinning permanent taskbar icons

## Which Desktop Model to Buy

| Machine       | Single-core performance       | Multi-core performance                  | System architecture modernity             | RAM upgradeability                   | Storage upgradeability                                           |
| ------------- | ----------------------------- | --------------------------------------- | ----------------------------------------- | ------------------------------------ | ---------------------------------------------------------------- |
| Mac mini 2012 | Low (≈500–700 Geekbench 6)    | Low–moderate (≈1100–2300)               | Very outdated Intel Ivy Bridge            | Yes (up to 16GB)                     | Excellent (2× SATA bays + SSD mods possible)                     |
| Mac mini 2014 | Moderate (≈600–900)           | Moderate–low (≈1500–7000 depending CPU) | Outdated Intel Haswell (dual-core common) | No (soldered)                        | Limited (single SATA drive)                                      |
| Mac mini 2018 | High (≈1100–1300)             | High (≈4000–7000+ i7)                   | Modern Intel Coffee Lake                  | Partial (up to 64GB depending model) | Moderate (proprietary PCIe SSD, replaceable)                     |
| Mac Pro 2013  | Moderate (≈700–1100 Xeon)     | High (≈4000–14,000 depending config)    | Aging Xeon + AMD GPU architecture         | Yes (up to 64 GB)                    | Moderate (proprietary Apple PCIe SSD, replaceable with adapters) |
| Mac Pro 2019  | Very high (≈1000–1200 Xeon W) | Very high (≈8000–20,000+)               | Modern modular workstation architecture   | Yes (up to 1.5TB ECC RAM)            | Excellent (fully modular PCIe SSD system)                        |
