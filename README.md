# ArmNN Magisk Module

This repository creates a Magisk module to update the Arm NN driver for the Android Neural Networks API.

## Tested device(s)

- Google Pixel 7 Pro

## Installation

On the device, download the latest module from [here](https://github.com/armflorentlebeau/magisk-module-armnn/releases/latest).

In a shell, enter `su` to run as root and CD into the directory where the module has been downloaded.

Install the module with:
```
magisk --install-module magisk_module_armnn_23-05.zip
```

## Enable disable module

From the tab `Modules` in Magisk enable/disable the module.

To check the version of ArmNN which is currently installed, run in a root shell:

```
/system/vendor/bin/hw/android.hardware.neuralnetworks@1.3-service-armnn -V
ArmNN Android NN driver for the Android Neural Networks API.
ArmNN v32.1.0
```
