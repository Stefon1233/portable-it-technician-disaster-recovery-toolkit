# Scenario 02 — Windows Boot Recovery

## Problem

A Windows computer fails to boot normally.

## Toolkit

USB 2 — BOOT-RECOVERY

## Troubleshooting Process

1. Connect the BOOT-RECOVERY USB.
2. Boot the computer from USB.
3. Open the Ventoy multiboot menu.
4. Select the Windows 11 installation/recovery environment.
5. Choose Repair your computer instead of installing Windows.
6. Open Troubleshoot.
7. Open Advanced Options.
8. Begin with the least-destructive recovery option.

## Recovery Options

- Startup Repair
- System Restore
- Uninstall Updates
- Command Prompt
- System Image Recovery
- UEFI Firmware Settings

## Disk Inspection

Use DiskPart to inspect storage:

    diskpart
    list disk
    list volume
    exit

Verify the correct disk before performing any operation that could modify storage.

## Lab Validation

The Windows Recovery Environment, Advanced Options, Command Prompt, and DiskPart were successfully accessed during testing.

No destructive recovery or installation operation was performed.

## Skills Demonstrated

- Windows recovery
- Boot troubleshooting
- Disk inspection
- Recovery environment navigation
- Safe troubleshooting practices
