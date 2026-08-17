# Scenario 05 — Hardware Diagnostics

## Problem

A computer experiences crashes, freezes, boot failures, or other instability that may be related to faulty memory.

## Toolkit

USB 2 — BOOT-RECOVERY

## Tool

Memtest86+

## Troubleshooting Process

1. Connect the BOOT-RECOVERY USB.
2. Boot into the Ventoy menu.
3. Launch Memtest86+.
4. Allow the memory diagnostic to run.
5. Monitor the pass count and error count.
6. Record the results.
7. If errors appear, investigate the installed RAM modules or memory configuration.

## Lab Result

During toolkit validation:

- Memtest86+ successfully booted.
- One complete test pass was performed.
- 0 memory errors were reported.

## Interpretation

A successful pass with zero errors demonstrates that the diagnostic environment works and did not detect memory errors during 
that test.

It does not guarantee that RAM can never fail or eliminate every possible hardware issue.

## Skills Demonstrated

- Hardware diagnostics
- RAM testing
- Bootable diagnostic tools
- Result interpretation
- Troubleshooting documentation
