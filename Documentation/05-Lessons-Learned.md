# Lessons Learned

## Separate Everyday Support from Disaster Recovery

Using two USB drives creates a clearer troubleshooting workflow.

USB 1 supports computers that can boot normally, while USB 2 provides bootable environments for offline diagnostics and recovery.

## Identify Disks Before Making Changes

Recovery environments can expose multiple disks and partitions.

Commands and utilities such as `lsblk`, DiskPart, and GParted should be used to identify storage devices before performing partition, formatting, imaging, or recovery operations.

## Recovery Work Should Start with the Least-Destructive Option

Troubleshooting should progress from diagnostics and inspection toward more invasive recovery procedures only when necessary.

This reduces the risk of unnecessary data loss.

## Virtualization Is Useful for Recovery Testing

VirtualBox provided an isolated environment for testing bootable media and recovery workflows without intentionally modifying a production operating system.

## Documentation Is Part of Troubleshooting

A technician toolkit is more useful when tools are accompanied by:

- Command references
- Checklists
- Recovery procedures
- Ticket templates
- Escalation guidance
- Screenshots
- Inventories

## Multiboot Media Simplifies Technician Work

Ventoy allows multiple recovery environments to coexist on one USB rather than requiring a separate drive for every ISO.

## Validation Matters

Simply copying utilities or ISO files to a USB does not prove that the toolkit works.

Booting and testing the major environments provided evidence that the recovery media could successfully reach the expected diagnostic and recovery interfaces.

## Safety Is Critical

Disk management, formatting, cloning, and operating-system installation can destroy data if the wrong disk is selected.

During this project, destructive operations were intentionally avoided while the recovery workflows and interfaces were validated.
