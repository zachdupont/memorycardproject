# Memory Card Project
Full image backups of various memory cards for 5th/6th generation video game consoles, intended as a time capsule of the pre-HD era in gaming.

None of these saves are personally mine, and the memory cards are typically sourced from untested lots on sites like eBay.

All memory cards are unencrypted and available to use in the emulator of your choice.

This is not a repository for unlocked or 100% saves.

# My Personal Methods

PS1/PS2 - I use an official Sony Memory Card Adapter for the Playstation 3, which can also plug in to a computer for use with programs such as MemcardRex for PS1 saves and ps3mca-tool for archiving PS2 saves. Requires the adapter itself and a mini-USB cable. (NOT Micro-USB as these adapters predate the official release and mass adoption of Micro-USB) I currently do not own a real PS2 or PS3 system.

Gamecube - A backwards-compatible Nintendo Wii with the Homebrew Channel and the GCMM (Gamecube/Wii Memory Manager) program installed. From there it's as simple as plugging in a physical Gamecube memory card in one of the slots and copying to an SD card or USB flash drive.

Original XBox - I use an adapter that is readily available on Amazon that can convert a USB connection to one of the 4 controller ports. Most flash drives under 2 GB will work and are read by the Xbox as an external memory unit, at which point I simply copy anything from either the internal hard drive or an actual memory unit. I then extract the save data using Xplorer360. My Xbox is also softmodded, which is useful because some games such as Ninja Gaiden Black encrypt their save data, meaning that you can't export them for use externally unless you're running a custom dashboard like UnleashX.

Xbox 360 - Probably the easiest one because you can use any USB flash drive regardless of storage capacity as a Memory Unit, and you can copy save data to it from the internal storage or other sources using the stock firmware. Actual memory cards for the 360 will require an older Phat model that read these because of the proprietary slot that they got rid of from the release of the Slim models onward, but your chance of finding these memory units out in the wild is slim-to-none considering most 360 consoles from launch came with a hard drive, and these particular memory units were only necessary for cheaper SKUs that lacked a hard drive and had very little internal storage such as the Xbox 360 Arcade, and were discontinued by the time the Slim models were rolled out as USB flash drives were becoming cheaper and Microsoft probably didn't think it was necessary to invest time and money in accomodating for a proprietary memory card slot during a system redesign when no one was really using them that much to begin with. Microsoft eventually added USB flash drive support for storing system data in 2010, around the time the Slim models released, and any model of Xbox 360 with firmware updated after 2010 will have this functionality with no additional hurdles.

# Useful Links: PS1/PS2

https://github.com/ShendoXT/memcardrex - For exporting real PS1 memory cards using adapters such as the DexDrive, PS3 Memory Card Adapter, and various other methods. PS1 saves are unencrypted by default and thus it's much simpler to back these up on a PC without spinning up a container as I see myself doing with PS2 memory cards. You can also use this utility to manipulate individual PS1 saves, export or import saves to virtual memory cards, and even write back to real PS1 memory cards using an adapter. This utility is only intended for use with PS1 memory cards as PS2 memory cards were shipped with Sony's proprietary MagicGate encryption, which means that homebrew developers are likely not comfortable with breaking Sony's encryption for legal reasons.

https://github.com/ShendoXT/memcardrex/blob/master/MONO.md - Additional instructions on getting MemcardRex to run on Linux via Mono as MemcardRex does not have a native Linux version, for those not using Windows.

https://hub.docker.com/r/islandc/ps3mca - Container image for reading and exporting real PS2 memory cards using the PS3 Memory Card Adapter, without needing a PS2/PS3. Although I can't confirm it's functionality with third-party adapters, it works great with my OEM Sony adapter for the PS3. This is a fully command-line based tool without a graphical user interface, and to my knowledge there are no MemcardRex equivalents for reading PS2 memory cards. Despite it's limitations, it is still adequate for reading, exporting, and archiving real PS2 memory cards without needing a PS2 with FreeMcBoot or a PS3 with a memory card adapter.

https://github.com/islandcontroller/ps3mca - Github repo for ps3mca Docker image with further setup instructions. 

https://rvvincelli.github.io/2017/03/01/bring-that-ps2-backup-back/ - Contains some useful info on adding ECC info to PS2 memory card dumps using ecc_check.exe (which is a quick but necessary step) as well as other useful tidbits of information regarding this topic, which I highly recommend reading through if you plan on doing this yourself.

# Useful Links: General

https://www.youtube.com/watch?v=ic-LtyX-ICg - An informative and well-produced video from the folks at My Life in Gaming demonstrating how to preserve memory cards and individual saves from a variety of systems, including Sony, Nintendo, Microsoft, and the Sega Dreamcast.
