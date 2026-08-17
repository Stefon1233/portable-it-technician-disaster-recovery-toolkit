# Scenario 03 — Offline File Recovery

## Problem

Windows cannot boot, but important user files must be recovered before additional repair or reinstallation is attempted.

## Toolkit

USB 2 — BOOT-RECOVERY

## Recommended Environments

- Ubuntu Desktop Live
- SystemRescue

## Troubleshooting Process

1. Boot the computer from the BOOT-RECOVERY USB.
2. Launch Ubuntu Live or SystemRescue through Ventoy.
3. Identify the internal storage device.
4. Inspect available partitions.
5. Mount the appropriate filesystem if required.
6. Verify that the user's files are accessible.
7. Connect separate destination storage.
8. Copy required files to the destination.
9. Verify the copied files.
10. Safely unmount storage before disconnecting it.

## Example Linux Commands

    lsblk
    df -h
    mount

## Safety

The original disk should be modified as little as possible during recovery.

Important files should be recovered before attempting destructive repair, formatting, partition changes, or operating-system 
reinstallation.

## Skills Demonstrated

- Linux live environments
- Storage identification
- Offline troubleshooting
- File recovery concepts
- Data-preservation practices
