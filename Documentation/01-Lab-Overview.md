# Portable IT Technician Disaster Recovery Toolkit — Lab Overview

## Project Objective

The objective of this project was to build and validate a portable two-USB toolkit for common IT support, troubleshooting, diagnostics, and disaster recovery tasks.

The toolkit separates everyday technician utilities from bootable recovery environments so that the appropriate tools are available whether an operating system is functional or unable to boot.

## Toolkit Design

### USB 1 — IT-TOOLKIT

USB 1 is designed for systems that can boot into their operating system.

It contains resources for:

- PowerShell troubleshooting and automation
- Network diagnostics
- Windows system utilities
- Software installation
- Driver support
- Recovery references
- Help desk documentation
- Portable applications

### USB 2 — BOOT-RECOVERY

USB 2 is a Ventoy-based multiboot recovery drive designed for systems requiring offline diagnostics or recovery.

It contains:

- Ubuntu Desktop Live
- SystemRescue
- GParted Live
- Memtest86+
- Clonezilla Live
- Windows 11 installation/recovery media

## Lab Environment

The project was built and tested using:

- macOS host system
- Oracle VirtualBox
- Ubuntu virtual machine
- Windows recovery environment
- Physical USB storage
- Ventoy multiboot platform

## Validation

Boot and recovery environments were tested through a VirtualBox recovery test environment.

Validation included:

- Ventoy multiboot functionality
- Linux live environment booting
- Windows Recovery Environment
- Windows Advanced Recovery Options
- DiskPart disk detection
- RAM diagnostics
- Disk and partition utilities
- SystemRescue diagnostic commands
- Clonezilla imaging interface

## Skills Demonstrated

- IT troubleshooting
- Help desk support
- Windows recovery
- Linux administration
- PowerShell
- Networking
- Virtualization
- Bootable media creation
- Hardware diagnostics
- Disk management
- Disaster recovery
- Technical documentation
