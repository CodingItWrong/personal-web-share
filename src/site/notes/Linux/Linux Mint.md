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
	- 1Password: [.deb from their web site](https://1password.com/downloads/linux)
	- Browsers
		- On high-RAM systems: Zen
		- On lower-RAM systems: Waterfox
	- Obsidian: via store
	- Visual Studio Code: [.deb from their web site](https://code.visualstudio.com/Download)
	- Gimp: via store
	- Development tools
		- Oh My ZSH: [install script](https://ohmyz.sh/#install)
		- Git: [[apt\|apt]]
		- Node: via [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#install--update-script)
		- Ruby: via [rbenv](https://github.com/rbenv/rbenv?tab=readme-ov-file#basic-git-checkout)
		- Postgres: apt