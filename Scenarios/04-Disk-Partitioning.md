# Scenario 04 — Disk and Partition Troubleshooting

## Problem

A computer has a disk or partition issue that cannot be adequately investigated from the installed operating system.

## Toolkit

USB 2 — BOOT-RECOVERY

## Tool

GParted Live

## Troubleshooting Process

1. Boot from the BOOT-RECOVERY USB.
2. Select GParted Live from the Ventoy menu.
3. Allow GParted to load.
4. Identify the correct physical disk.
5. Review existing partitions and filesystems.
6. Check disk capacity and partition layout.
7. Identify unallocated space or other partition configuration issues.
8. Document findings before making changes.

## Safety

Partition operations can cause permanent data loss.

Before resizing, deleting, creating, or formatting partitions:

- Verify the correct disk.
- Verify the correct partition.
- Back up important data.
- Understand the requested operation.
- Use the least-destructive troubleshooting method first.

## Lab Validation

GParted Live was successfully booted and the disk-management environment was inspected.

No destructive partition modifications were performed.

## Skills Demonstrated

- Disk identification
- Partition management concepts
- Bootable recovery utilities
- Storage troubleshooting
- Data-loss prevention
