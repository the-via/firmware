# Firmware for VIA

Apologies for the required work-around to GitHub being silly.

1. Click the link to the firmware.

2. Click the "Raw" button.

3. Right-click the page and "Save As..."

4. In the "Save As..." dialog, remove the ".txt" extension so the file is saved with a ".hex" or "*.bin" extension.

5. Install using your favorite flashing tool, such as QMK Toolbox, dfu-programmer, Atmel Flip, etc. Note that in many cases, you can hold down the top left key of your keyboard when inserting USB plug to put the PCB into "bootloader mode".

6. After flashing new firmware, restart the firmware application inside the flashing tool, or just unplug and plug USB.

7. VIA should detect your keyboard and display the default layout.
