# Clock Appliance Plan

## Goal

Turn the Macintosh SE into a self running clock while preserving the original files and avoiding irreversible changes.

## Design Requirements

1. Black and white output for the 512 by 342 pixel display.
2. Large, high contrast time display.
3. Slow motion or periodic inversion to reduce Cathode Ray Tube burn in.
4. Optional date line.
5. Optional family dedication line.
6. Auto launch after startup.
7. Configuration that can be changed from a modern Mac without editing the original internal hard drive.

## Preferred Control Model

Use file based control instead of modern style remote desktop control.

The Macintosh SE should:

1. Boot from the clock disk image.
2. Launch the clock app or HyperCard stack automatically.
3. Read a small settings file from the disk image or shared volume.
4. Update the displayed message, style, or schedule based on that settings file.

The modern Mac should:

1. Edit the settings file in the disk image first.
2. Later, update the settings file through AppleShare or another bridge if live networking is added.

## Implementation Options

1. HyperCard stack.
   * Easier to customize.
   * Period appropriate.
   * Good first working clock if memory permits.

2. Small classic Mac application.
   * Best final polish.
   * More work to build and transfer.
   * Can be optimized for System 6 and low memory.

3. Existing classic clock or screen saver.
   * Useful for testing.
   * Less personal.

## Anti Burn In Behavior

The clock should not sit in exactly one place forever. Acceptable behaviors:

1. Move the time slowly across the screen.
2. Invert black and white periodically.
3. Dim or blank the screen when not in use.
4. Use a small bouncing layout like a screen saver.

## First Milestone

The first working milestone is a bootable external image that opens a visible clock without touching the original internal drive.
