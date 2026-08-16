# USB 2 — BOOT-RECOVERY

## Purpose

USB 2 is a bootable multiboot recovery and diagnostic toolkit used when a computer cannot boot normally or requires offline troubleshooting.

## Boot Manager

- Ventoy 1.1.17

## Bootable Tools

- Ubuntu Desktop Live
- SystemRescue
- GParted Live
- Memtest86+
- Clonezilla Live
- Windows 11 installation/recovery media

## Use Cases

- Booting a PC when Windows will not start
- File recovery
- Disk and partition troubleshooting
- RAM diagnostics
- Disk imaging and cloning
- Operating system installation
- Windows recovery
- Live Linux troubleshooting
- Offline system diagnostics

## USB Structure

- `Linux/`
- `Windows/`
- `Recovery/`
- `Diagnostics/`

## Validation Performed

- Ventoy multiboot menu successfully loaded
- Ubuntu Live successfully booted
- SystemRescue successfully booted and diagnostic commands were tested
- GParted Live successfully booted
- Memtest86+ completed one pass with 0 errors
- Windows 11 Recovery Environment successfully loaded
- Windows Advanced Recovery Options and DiskPart were tested
- Clonezilla successfully reached its disk imaging and cloning interface

## Key Skills Demonstrated

- USB passthrough in VirtualBox
- Linux command-line administration
- Disk identification with `lsblk`
- Mounting and unmounting storage
- Ventoy installation and configuration
- Multiboot media creation
- Disk and partition troubleshooting
- Hardware diagnostics
- Disk imaging and cloning concepts
- Operating system recovery

## Safety

No destructive disk formatting, partition modification, cloning, or operating-system installation operations were performed during validation.
