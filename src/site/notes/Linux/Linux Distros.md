---
{"dg-publish":true,"dg-permalink":"linux/distros/","permalink":"/linux/distros/","dg-note-properties":{}}
---

My assessment of Linux distros for my use cases. My knowledge of Linux is limited, so anything on this page may not be fully correct.

# Overall Recommendation: [[Linux/Linux Mint\|Linux Mint]]

I agree with the common viewpoint that Linux Mint is the best introductory Linux distro. I think this is true not only for nontechnical users, but also for users like me: software developers who want their OS to mostly “just work” and not _require_ a lot of fiddling to get working.

Specifically, the benefits of Linux Mint I've seen are:

- Easy install
- Software store has a wide variety of apps, and it is fully-open source
- I've found updates to be reliable
- Easy to lock Linux kernel to an older LTS version, important to run [[Linux/Linux on Intel Macs\|on Mac]] for wireless drivers
- Built-in snapshot/restore functionality _should_ help in case of issues (I haven't tested it yet)

The only downsides:

- Doesn't support Wayland yet. But that's a totally fine tradeoff to get stability.
- Doesn't have as good touch screen support as Ubuntu. But although I have a laptop with touch screen support, this isn't as important to me as the other pros

# Alternatives I've Evaluated

## [Ubuntu](https://ubuntu.com/download/desktop)

### Pros

- Good support for touch interfaces, including an on-screen virtual keyboard
- Has an official ARM64 edition, which works virtualized [[Linux/Linux on Apple silicon\|on Apple silicon]]
- Supports Wayland

### Cons

- Snap Store is not fully open-source
- Harder to lock Linux kernel to an older LTS version to run on Mac minis

## [Pop_OS!](https://system76.com/pop/)

### Pros

- Beginner friendly
- Supports Wayland
- No Snap Store

### Cons

- Last time I tried it I ran into an issue where copy/paste didn’t work systemwide
- Apps I installed did not show icons in the GUI
- touch support

## [Elementary](https://elementary.io/)

### Pros

- Simple installation and setup
- Very polished UI

### Cons

- Their default store has limited app selection
- I ran into errors while applying updates, even when I had not installed much at all
- Does not support Wayland

## [NixOS](https://nixos.org/)

### Pros

- Reproducible system configurations from a single declarative file—this is kind of Nix’s whole thing

### Cons

- I could not get Mac mini wireless drivers working with it