# USB 2 - Boot & Recovery

## Overview
USB 2 is a Ventoy-based multiboot recovery drive designed for offline troubleshooting, operating-system recovery, disk management, hardware diagnostics, and imaging.

## Boot Platform
- Ventoy 1.1.17

## Bootable Environments
- Ubuntu 26.04 Desktop Live
- SystemRescue 13.02
- GParted Live 1.8.1-3
- Memtest86+ 8.10
- Clonezilla Live 3.3.3-15
- Windows 11 25H2 x64

## Capabilities
- Live Linux troubleshooting
- File recovery
- Disk and partition management
- RAM diagnostics
- Disk imaging and cloning
- Windows recovery environment
- Windows installation media
- Offline troubleshooting

## Validation Performed
- Ventoy multiboot menu successfully loaded
- GParted Live successfully booted
- SystemRescue successfully booted and diagnostic commands were tested
- Memtest86+ completed one pass with 0 errors
- Ubuntu Live successfully reached the desktop
- Windows 11 Recovery Environment successfully loaded
- Windows Advanced Recovery Options and DiskPart were tested
- Clonezilla successfully reached imaging/cloning modes

## Safety
No destructive disk, partition, cloning, formatting, or operating-system installation operations were performed during validation.
