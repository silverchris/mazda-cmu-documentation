# Hardware


## Main Processor
[NXP/Freescale i.mx6](doc/assets/IMX6DQRM.pdf)

Usually an I.MX6D dual core processor.
Some reports of I.MX6Q quad core processors have been found, but not verified.

```
/ # cat /proc/cpuinfo
Processor       : ARMv7 Processor rev 10 (v7l)
processor       : 0
BogoMIPS        : 1694.44

processor       : 1
BogoMIPS        : 1700.04

Features        : swp half thumb fastmult vfp edsp neon vfpv3
CPU implementer : 0x41
CPU architecture: 7
CPU variant     : 0x2
CPU part        : 0xc09
CPU revision    : 10

Hardware        : JCI i.MX 6Quad Core CMU Board
Revision        : 63000
Serial          : 0000000000000000

```

## Memory
1GB DDR(3?)

## Storage

### SPI-NOR
Device: spi0.0

- Contains the bootloader for both failsafe and normal operation.
- Contains the full failsafe image.
- Contains some configuration data
  
Macronix MX25L6445 - 16SOP package. 64MBIT/8Megabyte
Contains:

| Mount Point | Partition Name                | Device    | Flash Offset | Filesystem |
| ----------- | ----------------------------- | --------- | ------------ | ---------- |
|             | bootstrap                     | /dev/mtd0 | 0x000000     | N/A        |
|             | boot-select                   | /dev/mtd1 | 0x010000     | N/A        |
|             | ibc1                          | /dev/mtd2 | 0x020000     | N/A        |
|             | [ibc2](failsafe-boot.md)      | /dev/mtd3 | 0x040000     | N/A        |
|             | nv-config                     | /dev/mtd4 | 0x060000     | N/A        |
| /config     | config                        | /dev/mtd5 | 0x070000     | SquashFS   |
|             | jci-boot-diag                 | /dev/mtd6 | 0x0D0000     |            |
|             | [fail-safe](failsafe-boot.md) | /dev/mtd7 | 0x0E0000     | N/A        |
|             | update                        | /dev/mtd8 | 0x7E0000     | N/A        |


### eMMC
Device: mmcblk0

4GB

| Mount Point       | Use | Device         | Filesystem |
| ----------------- | --- | -------------- | ---------- |
| /mnt/data_persist |     | /dev/mmcblk0p2 | relfs      |
| /mnt/resources    |     | /dev/mmcblk0p1 | relfs      |



### NAND

Device: ffx00, ffx01

1GB

Main kernel and rootfs live here.
Uses proprietary FlashFx(ffxblk) driver from [DataLight](https://en.wikipedia.org/wiki/Datalight)

| Mount Point | Use    | Device       | Filesystem |
| ----------- | ------ | ------------ | ---------- |
|             | kernel | /dev/ffx00   |            |
| /           | rootfs | /dev/ffx01p1 | relfs      |
|             |        | /dev/ffx01p2 | relfs      |
|             |        | /dev/ffx01p3 | relfs      |
| /mnt/data   |        | /dev/ffx01p4 | relfs      |

## VIP

[Renaesas R5F35MCEJFB](doc/assets/R5F35MCEJFB.pdf)

Implements the communication between the main processor and the CAN/LIN busses.

Also performs watchdog function, and will reset the main processor if communication is disrupted. (handled by vim_app)


## I2C devices

| Bus-Address | Name                                                |
| ----------- | --------------------------------------------------- |
| 0-0018      | [aic310x](https://www.ti.com/product/TLV320AIC3100) |
| 1-0020      | [adv7180](#video-decoder)                           |
| 2-0010      | auth-ic                                             |

## Connectors

### Power/Communication
Sumitomo 6098-5611 (Unverified)

![CMU Connector](doc/assets/images/MZ3USAC0920_201B.svg)

| Pin | Use            |
| --- | -------------- |
| 2A  |                |
| 2B  |                |
| 2C  | Ground         |
| 2D  | Ground         |
| 2E  | HS CAN H       |
| 2F  | HS CAN L       |
| 2G  |                |
| 2I  | Local CAN      |
| 2J  | Local CAN      |
| 2K  | LIN            |
| 2L  | GND            |
| 2M  |                |
| 2O  | RS485 to TAU + |
| 2P  | RS485 to TAU - |
| 2Q  | 12V Accessory  |
| 2R  | 12V Constant   |
| 2S  | UART TX        |
| 2T  | UART RX        |



### USB
![USB Connector](doc/assets/images/MZ3USAC0920_201D.svg)

| Pin | Use   |
| --- | ----- |
| 4A  | GND   |
| 4B  | Data+ |
| 4C  | 5V    |
| 4D  | Data- |


Hirose GT17 series connector. One with B keying, one with C keying

| P/N              | Description    |
| ---------------- | -------------- |
| GT8-2428SCF(70)  | Crimp pin      |
| GT17HN-4DS-2C(C) | C keyed insert |
| GT17HN-4DS-2C(B) | B keyed insert |
| GT17HNS-4DS-HU   | Housing        |
| GT17HNS-4DS-5CF  | Shield Contact |

### Display

![Display Connector](doc/assets/images/MZ3USAC0920_201C.svg)

| Pin | Use    |
| --- | ------ |
| 3A  |        |
| 3B  | LVDS + |
| 3C  |        |
| 3D  | LVDS - |

Hirose GT17 series connector. A keying

| P/N              | Description    |
| ---------------- | -------------- |
| GT8-2428SCF(70)  | Crimp pin      |
| GT17HN-4DS-2C(A) | A keyed insert |
| GT17HNS-4DS-HU   | Housing        |
| GT17HNS-4DS-5CF  | Shield Contact |


### Audio Connector

![Audio Connector](doc/assets/images/MZ3USAC0920_201A.svg)

| Pin | Use                               |
| --- | --------------------------------- |
| 1A  | Rear Camera (Video Signal)        |
| 1B  | Rear Camera (Video Ground)        |
| 1C  | Rear Camera (Power +6V)           |
| 1D  | Rear Camera (Shield/Power Ground) |
| 1E  |                                   |
| 1F  |                                   |
| 1G  | DVD (Signal)                      |
| 1H  | DVD (Ground)                      |
| 1I  |                                   |
| 1J  |                                   |
| 1K  | iPod Video (Signal)               |
| 1L  | iPod Video (Ground)               |
| 1M  | Steering Wheel Control            |
| 1N  | Steering Wheel Control            |
| 1O  | Steering Wheel Control            |
| 1P  | Microphone  (Detect)              |
| 1Q  | Microphone  (Power)               |
| 1R  | Microphone  (Ground)              |
| 1S  | Microphone  (Signal +)            |
| 1T  | Microphone  (Signal -)            |
| 1U  |                                   |
| 1V  | Microphone (Shield)               |
| 1W  |                                   |
| 1X  | Audio Out (Shield)                |
| 1Y  | Audio Out (LH +)                  |
| 1Z  | Audio Out (LH -)                  |
| 1AA | Audio Out (RH +)                  |
| 1AB | Audio Out (RH -)                  |


| P/N          | Description  |
| ------------ | ------------ |
| A104954CT-ND | Crimp socket |
| 1717115-1    | Housing      |

### GPS Connector
Unknown

### GPS
Device: ttymxc2

ST STA8088F

## Wireless
wl1285q-bt possibly made by Texas Instruments, uses wl12xx driver

## Video Decoder
Analog Devices [adv7180](https://www.analog.com/media/en/technical-documentation/data-sheets/adv7180.pdf)