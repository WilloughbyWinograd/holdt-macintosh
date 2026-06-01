# Holdt Macintosh Restoration

Repository name: `holdt-macintosh`.

This repository tracks the restoration of Willoughby's grandfather's Apple Macintosh SE and the plan to turn it into a preserved, reversible clock appliance.

## Namesake

Holdt refers to Terry Holdt, Willoughby's maternal grandfather. The Team 6502 archive identifies him as the Product and Program Manager for Microcomputers at MOS Technology and as the 6502 Process Development Manager. He was part of the group that left Motorola in 1974 to build the affordable MOS Technology 6502 microprocessor, after earlier managing products around the Motorola 6800 family.

## Machine Identified

The prior photo session identified the computer as:

1. Apple Macintosh SE.
2. Model number M5011.
3. One megabyte of memory.
4. 800 kilobyte floppy drive.
5. 20SC hard disk.
6. Federal Communications Commission identifier BCG9GRM5011.
7. Barcode text most likely F721D7M5011, with some uncertainty because the source image was blurry.

## Current Status

As of 2026-06-01:

1. The computer powers on with a standard grounded IEC C13 computer power cable.
2. The keyboard is present.
3. The keyboard cable is missing.
4. The mouse is missing.
5. No data preservation work has been done yet.
6. The internal hard drive should be treated as fragile until it is copied.

## Restoration Priorities

1. Preserve the original contents before installing or changing anything.
2. Avoid opening the Cathode Ray Tube (CRT) area casually.
3. Inspect or remove the old Parameter Random Access Memory (PRAM) battery before repeated use.
4. Use reversible external storage first, preferably an external BlueSCSI v2 DB-25 for Macintosh.
5. Build the clock appliance on a separate boot image, not on the original internal hard drive.

## Immediate Hardware To Acquire

1. Apple Desktop Bus (ADB) keyboard cable, four pin mini DIN male to male.
2. Apple Desktop Bus (ADB) mouse.
3. External BlueSCSI v2 DB-25 for Macintosh.
4. microSD card for the BlueSCSI.
5. Optional: tools and service support for safe PRAM battery inspection.

## Intended Outcome

The target result is a Macintosh SE that:

1. Boots reliably from preserved or replacement media.
2. Keeps the original internal hard drive contents archived.
3. Auto launches a simple black and white clock.
4. Avoids static Cathode Ray Tube burn in by moving or inverting the clock display.
5. Can be updated from a modern Mac through disk images first, and possibly live networking later.

## Repository Layout

1. `docs/current-status.md`: known facts and open questions.
2. `docs/hardware-inventory.md`: machine, ports, missing parts, and photos to collect.
3. `docs/shopping-list.md`: parts to buy or borrow.
4. `docs/preservation-plan.md`: order of operations for saving the original files.
5. `docs/clock-appliance-plan.md`: design for the eventual clock setup.
6. `logs/`: dated restoration notes.
7. `photos/`: photo index only. Do not commit private disk images here.

## Data Handling Rule

Do not commit full disk images or personal files from the original Macintosh to GitHub by default. Store them locally and back them up separately. If any small screenshots or directory listings are useful, review them before committing.
