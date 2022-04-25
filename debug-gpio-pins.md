Found in libjcivim_api.so:VIMDEBUG_Init
/sys/class/gpio/%s/value","DO_TP1056"

DO_TP1056
DO_TP1053
DO_TP1054
DO_TP1057
DO_TP1027
DO_TP1029


/tmp/root # cat /sys/kernel/debug/gpio
GPIOs 0-31, gpio-0:
 gpio-16  (i2css_reset         ) out lo
 gpio-19  (DI_TV_DET           ) in  lo
 gpio-21  (DI_CAMERA_SEL       ) in  hi

GPIOs 32-63, gpio-1:
 gpio-40  (DO_TP1053           ) out lo
 gpio-42  (▒>ߺ▒▒L▒▒p▒▒   ) in  hi
 gpio-43  (DI_VIP_SHIFTR       ) in  lo
 gpio-44  (DI_MIC_SENSE        ) in  hi
 gpio-47  (DO_TP1054           ) out lo
 gpio-58  (spi_imx             ) out lo
 gpio-62  (spi_imx             ) out lo

GPIOs 64-95, gpio-2:
 gpio-83  (DO_GPS_WAKEUP       ) out hi
 gpio-84  (DO_WDI              ) out lo
 gpio-87  (DO_WDI_DISABLE      ) out hi
 gpio-90  (DO_SW_RESET         ) out hi
 gpio-93  (spi_imx             ) out lo
 gpio-94  (host1               ) in  hi
 gpio-95  (DO_HOST1_PWR        ) out hi

GPIOs 96-127, gpio-3:
 gpio-101 (DO_DEBUG_LED        ) out hi
 gpio-102 (DO_RS485_BUF_EN     ) out lo
 gpio-103 (DO_VIP_RESET        ) out hi
 gpio-106 (DI_ACC_SENSE        ) in  lo
 gpio-110 (otg                 ) in  hi
 gpio-111 (DO_OTG_PWR          ) out hi
 gpio-112 (DO_BT_EN            ) out hi
 gpio-115 (DO_TP1056           ) out lo
 gpio-121 (DO_WL_EN            ) out hi
 gpio-122 (DO_WL_IRQ           ) in  lo
 gpio-123 (DI_PN512_IRQ        ) in  lo

GPIOs 128-159, gpio-4:
 gpio-134 (DO_CODEC_RESET      ) out hi
 gpio-135 (DO_TP1029           ) out lo
 gpio-149 (DO_TP1027           ) out lo

GPIOs 160-191, gpio-5:
 gpio-161 (DO_GPS_RESET        ) out lo
 gpio-164 (sysfs               ) in  lo
 gpio-165 (sysfs               ) in  lo
 gpio-181 (DO_TP1057           ) out lo
 gpio-191 (DO_PN512_RST        ) out hi

GPIOs 192-223, gpio-6:

GPIOs 224-241, platform/GpioChip, GpioChip:
 gpio-224 (CAN Inhibit Sense   ) in  lo
 gpio-225 (Commander Detect    ) in  lo
 gpio-226 (USB Power Good      ) in  hi
 gpio-227 (Camera Power Good   ) in  lo
 gpio-228 (Mic Power Good      ) in  hi
 gpio-229 (Parking Brake       ) in  lo
 gpio-230 (Power Hold          ) out hi
 gpio-231 (TNS Illumination    ) in  lo
 gpio-232 (CAN_Day_Mode        ) in  lo
 gpio-233 (Safe_Shutdown       ) in  lo
 gpio-234 (Emergency           ) out lo
 gpio-235 (DO_USB_PWR_EN       ) out hi
 gpio-236 (DO_CAM_PWR_EN       ) out lo
 gpio-237 (DO_MIC_PWR_EN       ) out hi
 gpio-238 (MAP_Normal_Mode     ) out hi
 gpio-239 (MAP_Powerdown_Ready ) out lo
 gpio-240 (DO_MAP_BOOT_FAIL    ) out lo
 gpio-241 (CAN_Ignition_Status ) in  lo





