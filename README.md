# Renode setup
The Raspberry Pico needs configuration files for Renode to work properly.

* On MacOS, the installation location is `/Applications/Renode.app/Contents/MacOs`
* On Linux, the location for Debian, Fedora, and Arch is `/opt/renode`
* On Windows, the location is `C://Program Files/Renode`

To add the Pico configuration files:
1. Copy `rp2040_spinlock.py` and `rp2040_divider.py` to the `scripts/pydev` directory of your Renode installation.
1. Copy `rpi_pico_rp2040_w.repl` to the `platforms/cpus` directory.
# RTOS Lab 0

![CMake](https://github.com/uofu-advemb-26/rtos_lab0_Abed/actions/workflows/main.yml/badge.svg)

This project is my Lab 0 project for the embedded systems course. It demonstrates building, testing, and deploying a FreeRTOS application on the Raspberry Pi Pico W using CMake, the Raspberry Pi Pico SDK, and Unity.





