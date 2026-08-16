# USB 2 - Boot & Recovery Inventory

## Purpose
USB 2 provides bootable recovery, diagnostic, imaging, partitioning, and operating-system environments through Ventoy.

## Bootable Environments

| Tool | Version / Image | Purpose | Boot Tested |
|---|---|---|---|
| Ventoy | 1.1.17 | Multi-boot USB platform | Yes |
| Ubuntu Live | 26.04 Desktop AMD64 | Live operating system and file access | Yes |
| SystemRescue | 13.02 AMD64 | Advanced system and disk recovery | Yes |
| GParted Live | 1.8.1-3 AMD64 | Disk and partition management | Yes |
| Memtest86+ | 8.10 | RAM diagnostics | Yes - 1 pass, 0 errors |
| Clonezilla Live | 3.3.3-15 AMD64 | Disk imaging and cloning | Yes |
| Windows 11 | 25H2 x64 | Windows installation and recovery environment | Yes |

## USB Organization

```text
Ventoy/
├── Diagnostics/
│   └── Memtest86Plus-8.10.iso
├── Linux/
│   └── ubuntu-26.04-desktop-amd64.iso
├── Recovery/
│   ├── clonezilla-live-3.3.3-15-amd64.iso
│   ├── gparted-live-1.8.1-3-amd64.iso
│   └── systemrescue-13.02-amd64.iso
└── Windows/
    └── Win11_25H2_English_x64_v2.iso
```

## Validation
Each major boot environment was launched through Ventoy in a VirtualBox recovery test environment.

Validation included:
- Ventoy multi-boot menu
- GParted disk and partition inspection
- SystemRescue command-line recovery environment
- Memtest86+ memory diagnostic pass
- Ubuntu Live environment
- Windows 11 recovery and advanced troubleshooting tools
- Clonezilla disk imaging and cloning interface
