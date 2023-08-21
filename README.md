# RP2040-base-example
A simple dev board, created to test [RP2040-base](https://github.com/TT-392/RP2040-base)

Revision numbers get bumped to whole numbers when a physical version of the board has been tested.

# Tested functionality physical board rev 0.9 (identical to 1.0)
A sketch has been uploaded, which prints some stuff over cdc usb every second. This indicates working usb functionality, and working program memory.

![5 pcbs of revision 0.9 with black solder mask](./DSC09339.JPG "5 pcbs of revision 0.9 with black solder mask")
revision 0.9 of the pcb

# Known issues
1. No tought was given to which IO pins should be exposed, no analog pins have been exposed.
2. No debug LED.
