---
{"dg-publish":true,"dg-permalink":"vintage/mdd/","permalink":"/vintage/mdd/","dg-note-properties":{}}
---

The latest and most powerful Mac that can natively boot into classic Mac OS is the Power Mac G4 Mirrored Drive Door (MDD). Not all [models of MDD](https://everymac.com/systems/apple/powermac_g4/index-powermac-g4.html) support classic:

- Versions of the MDD released before 2003 do support booting into OS 9
- FireWire 800 versions of the MDD (released in 2003) do NOT support booting into OS 9
- The [1.25 GHz model released in 2003](https://everymac.com/systems/apple/powermac_g4/specs/powermac_g4_1.25_mdd.html) does support booting into OS 9; in fact, this model was created specifically because there was demand from A/V professionals for a machine that could still run their OS 9 media apps 

## Tech Specs
The 1.25 GHz MDD comes with one or (in rare cases) two 1.25 GHz PowerPC G4 processors.

It can take up to 2 GB of RAM, although Mac OS 9 can only see 1.5 GB of it.

## OS

The 1.25 GHz MDD came with a unique version of Mac OS 9 — 9.2.2.

If you need to install or reinstall 9.2.2, [the 9.2.2 disc](http://macintoshgarden.org/apps/mac-os-922-powermac-g4-mdd) is available for download on Macintosh Garden.

If you don’t want to install Mac OS X but only Mac OS 9, I found helpful instructions on [Vintage Mac Museum](https://vintagemacmuseum.com/reinstalling-mac-os-9-on-a-powermac-g4-mdd/):

> …a bootable OS 9 System Folder. I suspected this was included on the set of four CDs somewhere, but it isn’t a Finder-visible file. 
> 
> A bit of sleuthing in Terminal helped find the mystery location. The OS 9 software is in a hidden directory called *.images* on the first disc. Inside there are several files including *OS9General.dmg*. I was able to mount (open) this disk image to the desktop via the following Terminal command:
> 
> ```
> open /Volumes/Restore\ CD/.images/OS9General.dmg
> ```
>
> That takes a few minutes, then mounts a volume called OS 9 Content onto the desktop. Inside here are our old friends Applications (Mac OS 9) and System Folder, just as we know and love.

Copy those folders to your hard disk and then it should be selectable as a Mac OS 9 startup volume.