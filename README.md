
# 6-Pack Grbl_ESP32 CNC Controller

<img src="http://www.buildlog.net/blog/wp-content/uploads/2020/07/20200711_120633.jpg" width="600">

<img src="http://www.buildlog.net/blog/wp-content/uploads/2020/07/20200711_120737.jpg" width="600">

### Overview

This is a fully modular CNC controller that runs [Grbl_ESP32](https://github.com/bdring/Grbl_Esp32 "Grbl_Esp32 at github.com") firmware, or the next generation of Grbl_ESP32, [FluidNC](https://github.com/bdring/FluidNC "FluidNC at github.com") firmware.

### Features

- (1) **ESP32 Socket** designed to fit both narrow and wide (✪add widths) 2 x 19 pin types.
- (6) **Stepper Driver Sockets** which can be used for 6 axes (XYZABC) or any (2) can be ganged to allow dual motors on a single axis. These ganged motors can be controlled independently for axis squaring. Each driver socket has an independent enable/disable pin, and supports these types of drivers:
  - Standard Pololu/StepStick style driver modules.
  - Trinamic SPI type driver modules. These are the ultra quiet{✪electrically?} types with sensorless endstop capability.
  - External Driver with 5V opto isolators.
- (5) **CNC I/O Module Sockets** that provide interface access to your machine. Types include, but are not limited to, switch inputs, spindle control, and accessory control. Currently there are (9) modules available, listed [here](https://github.com/Longus/6-Pack_CNC_Controller/wiki/CNC-I-O-Module-List/ "CNC-I-O-Module-List")

[<img src="https://github.com/bdring/TMC2209_4x_DK/blob/main/images/tindie-logo.png" width="160">](https://www.tindie.com/products/33366583/6-pack-universal-cnc-controller/)
