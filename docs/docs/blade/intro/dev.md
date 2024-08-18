---
sidebar_position: 3
---
# Dev

The Dev Compute Blade contains all feature of TPM

![Dev Compute Blade](/img/blade/mk4-k-dev.png)

## DIP Switch

:::danger
Only change switch positions when the Blade is unplugged from power
:::

|         Switch       |   Left   |   Right  |
| :------------------- | :------: | :------: |
| 1 - Write Protection | Disabled | Enabled  |
| 2 - Wi-Fi            | Enabled  | Disabled |
| 3 - Bluetooth        | Enabled  | Disabled |

:::warning
To enable write protection, changes are required to the bootloader. Follow the steps in the official [documentation](https://www.raspberrypi.com/documentation/computers/compute-module.html#cm4bootloader).
:::

## USB-C USB-A Switch

The compute module can only operate one USB port at a time. There is a switch to enable which port you would like to utilize.

## Block Scheme
![Dev Block Scheme](/img/hardware/dev-block-scheme.png)
