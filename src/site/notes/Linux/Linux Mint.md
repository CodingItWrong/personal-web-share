---
{"dg-publish":true,"dg-permalink":"linux/mint/","permalink":"/linux/mint/","dg-note-properties":{}}
---

Setup instructions for my Mint setups, and miscellaneous notes.

- Desktop environment
	- Cinnamon edition if at all possible. Taskbar app pinning just works
	- In lower-power or virtual environments, can consider MATE or XFCE, but setting up persistent toolbar items is more cumbersome
- Version to install
	- Non-Apple hardware: [latest version](https://www.linuxmint.com/download.php), Cinnamon edition
	- Apple hardware: [22.1, Cinnamon edition](https://www.linuxmint.com/edition.php?id=319). This is to start not on the Linux 6.8 kernel, which as of this writing is required to build Broadcom WiFi drivers
- Drivers
	- Apple hardware: Broadcom WiFi drivers. Install in ???
- Kernel
	- Updates managed in ???
	- Apple hardware: do NOT update past 6.8. Update to 6.8 latest
	- Non-Apple hardware: update to latest
- Installing my key apps
	- 1Password: from their web site
	- Browsers
		- Zen on high-RAM systems
		- Waterfox on lower-RAM systems
	- Obsidian: via store
	- Visual Studio Code: via .deb
	- Development tools
		- Git: [[apt\|apt]]
		- Node: via nvm
		- Ruby: vi rbenv
		- Postgres: apt