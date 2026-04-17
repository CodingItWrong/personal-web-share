---
{"dg-publish":true,"dg-permalink":"linux/onapplesilicon/","permalink":"/linux/onapplesilicon/","dg-note-properties":{}}
---

## On Metal
[Asahi Linux](https://asahilinux.org/docs/platform/feature-support/overview/?utm_source=chatgpt.com) is the main way to run Linux on bare metal on Apple silicon. But it currently only fully supports M1 and M2 chips.

## Virtualized
Need an ARM64 edition so that you are using the same processor architecture, not emulating.

I recommend [Ubuntu Desktop ARM64](https://ubuntu.com/download/desktop)  in [UTM](https://getutm.app/). I have a working VM with settings:

- RAM: 4096 MiB
- CPU: default
- CPU Cores: default
