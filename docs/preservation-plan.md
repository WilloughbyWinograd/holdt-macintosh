# Preservation Plan

## Goal

Copy the original 20SC hard disk contents before any customization. The original drive may be fragile, and the computer has sentimental value.

## Sequence

1. Confirm basic power on behavior.
   * Record startup chime status.
   * Photograph the screen.
   * Listen for hard drive spin up or repeated clicking.

2. Acquire basic input hardware.
   * Apple Desktop Bus keyboard cable.
   * Apple Desktop Bus mouse.
   * Connect devices only while the Macintosh SE is powered off.

3. Acquire external storage.
   * External BlueSCSI v2 DB-25 for Macintosh.
   * microSD card.

4. Prepare BlueSCSI images on the modern Mac.
   * Clean System 6.0.8 boot image.
   * Blank archive image for the original internal hard disk contents.
   * Separate clock experiment image.

5. Boot the Macintosh SE from external BlueSCSI.
   * Do not install anything on the internal drive.
   * Mount the internal hard disk if it is healthy enough.

6. Copy the internal hard disk contents.
   * Copy to the archive image.
   * Preserve classic Mac files inside disk images or encoded archives so resource forks survive.

7. Back up the archive image.
   * Keep at least one local copy outside the working microSD card.
   * Do not commit the disk image to GitHub by default.

8. Start clock work only after the archive exists.
   * Use the separate clock image.
   * Keep the original internal hard drive untouched unless a deliberate preservation decision is made later.

## Verification Checklist

1. Archive image mounts in a classic Mac emulator or disk image tool.
2. Directory listing of the original hard drive has been captured.
3. Archive image has at least one verified backup copy.
4. The working clock image is separate from the archive image.
