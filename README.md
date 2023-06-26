# Handwire Helpers

A collection of PCBs aimed at supporting handwired dactyl-ish keyboards. The goal is faster, simpler assembly (by offloading the key matrix from the handwiring to the PCB) and flexibility in placement of keys and connectors.

## Matrix PCBs

### Handwire Helper
Supports 8 columns, 4 rows for the first six columns and 5 for the last 2 (thumb) columns.  The first row is the pin towards the microcontroller connections (narrow side). On the MCU side there are 8 pins for the columns and 5 for the rows, with the final pin as an (unnecessary) ground.

The intent is to connect keyswitches to the PCB using hotswap sockets, soldered to [ribbon cables with DuPont connectors on the other side](https://www.adafruit.com/product/3141), which can plug in to the header on the long side of the PCB.

This lets the keyspacing be determined by a 3D printed case, independent of the PCB, so that electronics can be reused as keyboard designs change. This also means that different switch types can be supported, without prior consideration in the PCB design.

The microcontroller can be similarly connected to this board by jumpers, allowing flexibility in case design, and in placement of the USB plug.

Version 0.1 has been successfully manufactured and functionality has been tested and verified.
