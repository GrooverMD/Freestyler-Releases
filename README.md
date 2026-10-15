# Freestyler

**A style designer for Embarcadero FireMonkey (FMX).**
Freestyler is a replacement for the RAD Studio Style Designer. It runs as its own
application or inside RAD Studio 13, where it opens whenever you edit a TStyleBook.

**[Download the latest release](https://github.com/GrooverMD/Freestyler-Releases/releases/latest)**

## Features

**Designing**
- Ribbon interface with a dark, Inventor-style theme
- Structure view with drag and drop; a dropped control can be aligned as it is created
- Object Inspector that expands sets, margins, padding, scale and other grouped properties
- Collapsible component palette using the RAD Studio component icons
- Canvas with zoom from 25% to 1600%, a checker, black or white background, and a Centre command

**Editing on the canvas**
- Selection frame with resize handles that show only where the control's Align and Anchors allow resizing
- Live width and height readouts; parent container outlined and labelled
- Snap and keyboard nudge
- Eyedropper, Fill and Stroke paint tools
- Colour editor with solid colours and gradients (add, move and remove stops)
- Full undo and redo

**Output**
- Opens and saves standard `.style` files
- Per-platform builds: one design, with overrides for Windows, macOS and Linux, built into a separate style for each

**RAD Studio integration**
- Tools > Freestyler Style Designer...
- Double-clicking a TStyleBook opens it in Freestyler; every save goes straight back into the form

## Requirements

- Windows 10 or 11, 64-bit
- For the IDE add-in: RAD Studio 13 / Delphi 13 (64-bit IDE)

## Installing

1. Download `FreestylerSetup-<version>.exe` from [Releases](https://github.com/GrooverMD/Freestyler-Releases/releases).
2. Run it. Windows may show "Windows protected your PC" because the installer is not yet
   code-signed: click **More info**, then **Run anyway**.
3. To use Freestyler inside RAD Studio, tick **RAD Studio add-in** during setup, then in RAD Studio choose
   **Component > Install Packages > Add...** and select `FreestylerIDE370.bpl` from the `IDE` folder
   where Freestyler was installed.

## Reporting problems

Open an [issue](https://github.com/GrooverMD/Freestyler-Releases/issues) with the version (File > About),
what you did, and the `.style` file if you can share it.

## Licence

Freestyler is proprietary software, free to evaluate under the terms in [LICENSE](LICENSE).
The source code is not public.

Copyright (c) 2024-2026 Mark S Day. All rights reserved.

RAD Studio, Delphi and FireMonkey are trademarks of Embarcadero Technologies, Inc. Freestyler is not
affiliated with or endorsed by Embarcadero. Component icons are loaded from your RAD Studio installation
and remain Embarcadero's property.
