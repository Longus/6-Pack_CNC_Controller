
# 6-Pack Grbl_ESP32 CNC Controller

A fully populated board:

<img src="http://www.buildlog.net/blog/wp-content/uploads/2020/07/20200711_120633.jpg" width="600">

A bare board (as shipped, before installation of the CNC I/O Module Supports which are included):

<img src="http://www.buildlog.net/blog/wp-content/uploads/2020/07/20200711_120737.jpg" width="600">

### Overview

This is a fully modular CNC controller that runs [Grbl_ESP32](https://github.com/bdring/Grbl_Esp32 "Grbl_Esp32 at github.com") firmware, or the next generation [FluidNC](https://github.com/bdring/FluidNC "FluidNC at github.com") firmware.

### Features

- (1) **ESP32 Socket** designed to fit 1.0" 1.1" or 1.2" width ESP32 Dev Kit with 2 x 19 pins
- (6) **Stepper Driver Sockets** which can be used for 6 axes (XYZABC) or any (2) can be ganged to allow dual motors on a single axis. These ganged motors can be controlled independently for axis squaring. Each driver socket has an independent enable/disable pin, and supports these types of drivers:
  - Standard Pololu/StepStick style driver modules
  - Trinamic SPI type driver modules. These are the ultra quiet types with sensorless endstop capability
  - External Driver with 5V opto isolators
- (5) **CNC I/O Module Sockets** that provide interface access to your machine. Types include, but are not limited to, switch inputs, spindle control, and accessory control. Currently there are (9) modules available, listed [here](https://github.com/Longus/6-Pack_CNC_Controller/wiki/CNC-I-O-Module-List/ "CNC-I-O-Module-List")
- (1) **Micro SD card slot**
- (1) **JTAG Programming/Debugging connector** (or access to addition I/O pins)
- (1) **5v DC power supply**

For more detail, see the [Wiki](https://github.com/Longus/6-Pack_CNC_Controller/wiki) and the video [A New Universal CNC Controller for Grbl_ESP32](https://www.youtube.com/watch?v=IMwXUbWLic0).

[<img src="https://github.com/bdring/TMC2209_4x_DK/blob/main/images/tindie-logo.png" width="160">](https://www.tindie.com/products/33366583/6-pack-universal-cnc-controller/)
