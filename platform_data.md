- [i2c](#i2c)
- [SPI](#spi)
- [UART](#uart)
- [GPIO](#gpio)

## i2c

| i.mx6 register base | irq  | i2c adapter | bus speed | device                          |
|---------------------|------|-------------|-----------|---------------------------------|
| 0x21A0000           | 0x44 | 0           | 104kbit/s | Audio Codec (aic310x)           |
| 0x21A4000           | 0x45 | 1           | 104kbit/s | Video Decoder/Capture (adv7180) |
| 0x21A8000           | 0x46 | 2           | 50kbit/s  | Apple "auth-ic"                 |

## SPI

| SPI Master | Device        | Speed |
|------------|---------------|-------|
| 1          | SPI-NOR Flash | 20MHz |
| 2          | VIP           | 4MHz  |
| 4          | ?             | 1MHz  |


## UART
| i.mx6 uart | linux Uart   | Use           |
|------------|--------------|---------------|
| uart1      | /dev/ttymxc0 | LVDS/Display? |
| uart2      | /dev/ttymxc1 | console       |
| uart3      | /dev/ttymxc2 | GPS           |
| uart4      | /dev/ttymxc3 | Bluetooth     |
| uart5      | /dev/ttymxc4 | TDS           |

## GPIO


| i.mx6      | Linux GPIO | Use                   | Name             | sysfs_name      | active low | initial value | direction | direction may change | Notes                                                                      |
|------------|------------|-----------------------|------------------|-----------------|------------|---------------|-----------|----------------------|----------------------------------------------------------------------------|
| GPIO1_IO16 | 0x10       |                       | i2css_reset      |                 |            |               |           |                      | Apple auth-ic                                                              |
| GPIO1_IO19 | 0x13       |                       | TV Detec         | DI_TV_DET       | 0          | 0             | 1         | 1                    |                                                                            |
| GPIO1_IO21 | 0x15       |                       | Camera Select    | DI_CAMERA_SEL   | 0          | 0             | 1         | 1                    |                                                                            |
| GPIO2_IO08 | 0x28       |                       | TP1053           | DO_TP1053       | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO2_IO10 | 0x2A       |                       | VIP IRQ          | DI_VIP_IRQ      | 1          | 1             | 1         | 1                    |                                                                            |
| GPIO2_IO11 | 0x2B       |                       | Reverse          | DI_VIP_SHIFTR   | 1          | 0             | 1         | 1                    |                                                                            |
| GPIO2_IO12 | 0x2C       |                       | Mic. Sense       | DI_MIC_SENSE    | 0          | 0             | 1         | 1                    |                                                                            |
| GPIO2_IO15 | 0x2f       |                       | TP1054           | DO_TP1054       | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO2_IO26 | 0x3A       | VIP Chip Select       |                  | ecspi2-ss0      |            | 1             | 0         |                      | Seen in mx6q_cmu_board_init. Pad set to alt function with iomux GPIO2_IO26 |
| GPIO2_IO30 |            | NOR Flash Chip select |                  | ecspi1-ss0      |            | 1             | 0         |                      | Seen in mx6q_cmu_board_init. Pad set to alt function with iomux GPIO2_IO30 |
| GPIO3_IO19 | 0x53       |                       | GPS Wakeup       | DO_GPS_WAKEUP   | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO3_IO20 | 0x54       |                       | Watchdog Interr  | DO_WDI          | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO3_IO23 | 0x57       |                       | Watchdog Disable | DO_WDI_DISABLE  | 0          | 1             | 0         | 1                    |                                                                            |
| GPIO3_IO26 | 0x5A       |                       | Reset            | DO_SW_RESET     | 1          | 1             | 0         | 1                    |                                                                            |
| GPIO3_IO29 | 0x5D       |                       |                  |                 |            |               |           |                      | chip select??                                                              |
| GPIO3_IO30 | 0x5E       | USB OTG Over current  |                  |                 |            |               |           |                      | usb_oc.ko                                                                  |
| GPIO3_IO31 | 0x5F       |                       |                  | DO_HOST1_PWR    |            |               |           |                      | USB                                                                        |
| GPIO4_IO05 | 0x65       |                       | Debug LED        | DO_DEBUG_LED    | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO4_IO06 | 0x66       |                       | DO_RS485_BUF_EN  | DO_RS485_BUF_EN | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO4_IO07 | 0x67       |                       | Reset VIP        | DO_VIP_RESET    | 1          | 1             | 0         | 1                    |                                                                            |
| GPIO4_IO10 | 0x6A       |                       | ACC_Sense        | DI_ACC_SENSE    | 1          | 1             | 1         | 1                    |                                                                            |
| GPIO4_IO14 | 0x6E       | USB OTG Over current  |                  |                 |            |               |           |                      | usb_oc.ko                                                                  |
| GPIO4_IO15 | 0x6E       |                       |                  | DO_OTG_PWR      |            |               |           |                      |                                                                            |
| GPIO4_IO16 | 0x70       | Bluetooth RF Kill     |                  | DO_BT_EN        |            |               |           |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO4_IO19 | 0x73       |                       | TP1056           | DO_TP1056       | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO4_IO25 | 0x79       | WiFi RF Kill          |                  | DO_WL_EN        |            |               |           |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO4_IO26 | 0x7A       | WiFi IRQ              |                  | DO_WL_IRQ       |            |               |           |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO4_IO27 | 0x7B       |                       | NFC IRQ          | DI_PN512_IRQ    | 1          | 0             | 1         | 1                    |                                                                            |
| GPIO4_IO28 | 0x7C       |                       |                  |                 |            |               |           |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO5_IO06 | 0x86       |                       |                  | DO_CODEC_RESET  |            | 0             | 0         |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO5_IO07 | 0x87       |                       | TP1029           | DO_TP1029       | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO5_IO20 | 0x94       |                       |                  | DO_LVDS_PWRDWN  |            | 1             | 0         |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO5_IO21 | 0x95       |                       | TP1027           | DO_TP1027       | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO6_IO00 | 0xA0       |                       | LVDS Mode Select | DO_LVDS_MS      |            | 1             | 0         |                      | Seen in mx6q_cmu_board_init                                                |
| GPIO6_IO01 | 0xA1       |                       | GPS Reset        | DO_GPS_RESET    | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO6_IO04 | 0xA5       |                       | LVDS INT         |                 |            |               |           |                      |                                                                            |
| GPIO6_IO05 | 0xA4       |                       | LVDS LineFault   |                 |            |               |           |                      |                                                                            |
| GPIO6_IO21 | 0xB5       |                       | TP1057           | DO_TP1057       | 0          | 0             | 0         | 1                    |                                                                            |
| GPIO6_IO31 | 0xBF       |                       | NFC Reset        | DO_PN512_RST    | 1          | 1             | 0         | 1                    |                                                                            |