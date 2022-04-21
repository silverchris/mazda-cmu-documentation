# Hardware


## Main Processor
[NXP/Freescale i.mx6](pdf/IMX6DQRM.pdf)


## Storage

### SPI-NOR
Macronix MX25L6445 - 16SOP package. 64MBIT/8Megabyte
Contains:
| Mount Point | Partiton Name | Device | Flash Offset | Filesystem |
| ---------- | ------------- | ----------- |------------ | ----------- |
||bootstrap || 0x000000|
|| boot-select || 0x010000 |
|| ibc1 || 0x020000 |
|| [ibc2](failsafe-boot.md) || 0x040000 |
|| nv-config | |0x060000 |
| /config| config | | 0x070000 | SquashFS
|| jci-boot-diag || 0x0D0000|
|| [fail-safe](failsafe-boot.md) || 0x0E0000 |
||update || 0x7E0000|


### eMMC
| Mount Point | Use | Device | Filesystem |
|------------ | --- | ------ | ---------- |
| /mnt/data_persist | | /dev/mmcblk0p2| |
| /mnt/resources | | /dev/mmcblk0p1| |



### NAND
Main kernel and rootfs live here.
| Mount Point | Use | Device | Filesystem |
|------------ | --- | ------ | ---------- |
| | kernel | /dev/ffx00 | |
| / | rootfs | /dev/ffx01p1 | relfs |


## VIP
[Renaesas R5F35MCEJFB](pdf/R5F35MCEJFB.pdf)

Implements the communication between the main processor and the CAN/LIN busses.

Also performs watchdog function, and will reset the main processor if communication is disrupted. (handled by vim_app)


