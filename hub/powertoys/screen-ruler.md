---
title: PowerToys Screen ruler utility for Windows
description: Screen ruler allows you to quickly measure pixels on your screen based on image edge detection.
ms.date: 04/27/2022
ms.topic: article
no-loc: [PowerToys, Windows, Screen ruler, Win]
---

# Screen ruler utility

Screen ruler allows you to quickly measure pixels on your screen based on image edge detection. This was inspired by [Pete Blois's Rooler](https://github.com/peteblois/rooler).

## How to activate

Just press <kbd>⊞ Win</kbd>+<kbd>Shift</kbd>+<kbd>M</kbd> to activate and then select which tool you want to measure with. To exit, just hit <kbd>Esc</kbd> or click the toolbar.

## How to use

- Bounds (Dashed square symbol): This is a bounding box.  Click and drag with your mouse.  If you hold <kbd>Shift</kbd>, the box will stay until you cancel the interaction
- Spacing (+ symbol): This will measure horizontal and vertical spacing at the same time.  Click the symbol and move your mouse to your target location.
- Horizontal (- symbol): This will measure only horizontal spacing.  Click the symbol and move your mouse to your target location.
- Vertical (| symbol):This will measure only vertical spacing.  Click the symbol and move your mouse to your target location.
- Cancel interaction: <kbd>Esc</kbd> or mouse click

## Settings

From the Settings menu, the following options can be configured:

| Setting | Description |
| :--- | :--- |
| Activation shortcut | The customizable keyboard command to turn on or off the toolbar. |
| Capture screen continuously during measuring | When off, the utility takes a single snapshot of your screen. When this is turned on, the utility will attempt real-time detection. This mode will consume more resources when in use. |
| Per color channel edge detection | Test all color channels are within a tolerance distance from each other. Otherwise, check that the sum of all color channels differences is smaller than the tolerance. |
| Pixel tolerance for edge detection | A value between 0-255. A higher value will provide a higher variation so it will be more forgiving with things like gradients and shadows. |
| Draw feet on the cross | Adds small feet for additional visual capture. |
| Line color | The color for the line that does the measuring. |
