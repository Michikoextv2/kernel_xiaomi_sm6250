# Xiaomi Miatoll (sm6250) Custom Kernel

This repository contains the custom kernel source code and releases for Xiaomi miatoll-platform devices (device codename: miatoll).

## Overview

This kernel is built with a focus on stability and efficiency while maintaining balanced performance. It is designed to work reliably across AOSP-based ROMs, MIUI, HyperOS, and other ported distributions.

## Supported Devices

| Device | Codename |
|---|---|
| Xiaomi POCO M2 Pro | `gram` |
| Xiaomi Redmi Note 9S | `miatoll` |
| Xiaomi Redmi Note 9 Pro | `joyeuse` |
| Xiaomi Redmi Note 9 Pro Max | `excalibur` |
| Xiaomi Redmi Note 10 Lite | `curtana` |

## Kernel Variants

* **SuperPotato**
  * **Base:** LineageOS
  * **Description:** Built upon the LineageOS kernel tree.

## ROM Compatibility

| ROM Type | Status |
|---|---|
| AOSP-based ROMs | Supported |
| MIUI | Supported |
| HyperOS | Supported |
| Ported ROMs | Supported |

## Flashing Instructions

1. Reboot the device into a custom recovery.
2. Flash the kernel `.zip` package.
3. Reboot the system.

*Note: It is highly recommended to back up your current `boot` and `dtbo` partitions before flashing.*

## Credits and Acknowledgments

* [clarencekopitiam](https://github.com/clarencekopitiam/kernel_xiaomi_sm6250) for the original kernel source.
* [AzyrRuthless](https://github.com/AzyrRuthless/kernel_xiaomi_sm6250) for the fork base reference.
* All open-source contributors and testers.
