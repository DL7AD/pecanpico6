# Pecan Pico 6 - Pico solar powered APRS tracker

This are the EGALE CAD files for the Pecan Pico 6 project. Pecan Pico is a very small solar powered balloon APRS tracker
in the size of an AAA battery cell. It's powered by a LiFePO4 battery which can be charged by solar cells.

The PCB itself has all the power management features (charging and discharging) integrated, so it needs no external
power supply. It has:
- GPS receiver (ublox MAX7/8)
- NXP LPC1114 microcontroller
- Si4063 transmitter (for APRS transmission)
- Bosch BMP180 (for measure temperature and airpressure)

With the recommended LiFePO4 (200mAh AAA) battery cell, the tracker has a weight of just 13g. It's main
purpose is high altitude ballooning. This particular tracker has been made for super pressure balloons which can fly
for weeks. The solar powered PCB can almost stay alive forever.

The source code for the NXP LPC1114 on the board can be found here: https://www.github.com/DL7AD/pecan-lpc11xx

![Pecan Pico 6](https://kt5tk.files.wordpress.com/2015/08/dscn7470.jpg?w=800)
