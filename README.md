# Marlin 3D Printer Firmware
<img align="right" src="../../raw/1.1.x/buildroot/share/pixmaps/logo/marlin-250.png" />

## short description 
This firmware is customized version of the original [Marlin-1.1.6](https://github.com/MarlinFirmware/Marlin/tree/1.1.6) firmware.

The necessary parameters for delta printers were taken from the CN firmware (from sd card), and modified for the Linear Plus model.

If you want to use this firmware for a non plus model, you need to change the following parameters:
   
DELTA_PRINTABLE_RADIUS  116.0 // 90.0 for pulley

DELTA_RADIUS		116.0 // 90.4 for pulley

DELTA_DIAGONAL_ROD	269   //

DELTA_HEIGHT		300   // no sense to change, because have a automatic calibration

Z_PROBE_OFFSET_FROM_EXTRUDER -24.4 // height of a V2 probe (from the switch bottom to nozzle).


The latest firmwares has a mode of auto-calibration (G33).

For use this feature you need to assemble the probe and connect it to the pins of the Z- (https://www.thingiverse.com/thing:1976680)

More information about of the auto-calibration see in the documentation: http://marlinfw.org/docs/gcode/G033.html



