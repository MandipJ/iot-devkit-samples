# Sound Bar


## Introduction
This example show how to use a Led Bar to show ambient sound level. 


## Hardware requirements

[Grove Sound Sensor](http://wiki.seeed.cc/Grove-Sound_Sensor/)connected to an analog port
[Grove Led Bar](http://wiki.seeed.cc/Grove-LED_Bar/) connected to digital ports for data and power

## Supported boards

This sample has been tested on
- Up2 board

The sample might need minor modifications depending on the board and shield you are using.

## Software requirements

The following libraries need to be installed on your target platfrom for this sample to work

[UPM](https://github.com/intel-iot-devkit/upm) & [MRAA](https://github.com/intel-iot-devkit/mraa) libraries

## Setup
Follow the steps listed in the hardware requirements section.

## Notes

Mraa I/O operations require permissions to UNIX character devices and sysfs not commonly granted to normal users by default. To avoid permission issues you can run your application as root by killing the target tcf-agent and reconnecting to your board as root. The systemd journal/logfile will reflect this as mraa logs most things to syslog. More information is available [here](https://github.com/intel-iot-devkit/mraa/blob/master/docs/debugging.md).
