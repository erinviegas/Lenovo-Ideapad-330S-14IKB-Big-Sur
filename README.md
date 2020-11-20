# Lenovo Ideapad 330S-14IKB

## Hardware Upgrades
- Added additional Crucial 2400 DDR4 4GB RAM.
- Removed Intel Optane and replaced with a Kingston 240GB NVMe M.2 SSD. (macOS)
- Removed 1TB Internal Hard Drive and replaced with a Crucial 500GB SSD. (Windows 10)
- Removed Intel WiFi card and replaced with Lenovo Branded Broadcom BCM94352Z.

## Issues
- Audio issue after sleep. Can be fixed by going to the sound preferences and switching the inputs.

## BIOS Settings
- Upgrade to the latest BIOS.
- If yours came with Intel Optane, you need to disable that and use AHCI Legacy mode (Not RST).
- Disable secure boot and unload optimized defaults for windows 10.

### Full installation tutorial linked in the repository description.

### Credits
- [dortania](https://github.com/dortania) for the install guide.
- [acidanthera](https://github.com/acidanthera) for OpenCore and kexts.
- [zhen-zen](https://github.com/zhen-zen) for YogaSMC.
- [kasti0](https://github.com/kasti0) and [lucrative-menace](https://github.com/lucrative-menace) for the LID fix.
