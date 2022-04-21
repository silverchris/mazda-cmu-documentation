# Failsafe Boot/IBC2

Failsafe boot is launched when the first byte of the boot-select flash location(SPI-NOR:0x010000) is set to 0x00. The bootstrap code loads IBC2 from SPI-NOR:0x040000 into memory at OCRAM:0x00912000, then jumps to location 0x009126E0, starting IBC2.


## IBC2 Header

IBC2 then loads the failsafe boot image into memory at ????(Possibly at or around DDR:0x80000)

IBC2 then looks for it's 512 byte header.

```
Offset(h) 00 01 02 03 04 05 06 07 08 09 0A 0B 0C 0D 0E 0F

00000000  54 4F 4F 42 03 00 00 00 00 00 00 00 00 00 00 00
00000010  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000020  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000030  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000040  00 00 00 00 14 00 00 00 58 A8 21 00 01 00 00 00
00000050  D5 10 00 00 02 00 00 00 14 00 00 00 77 00 00 00
00000060  D6 10 00 00 01 00 00 00 01 00 00 00 14 00 00 00
00000070  28 0F 4C 00 D7 10 00 00 08 26 00 00 00 00 00 00
00000080  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000090  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000000A0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000000B0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000000C0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000000D0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000000E0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000000F0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000100  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000110  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000120  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000130  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000140  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000150  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000160  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000170  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000180  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
00000190  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000001A0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000001B0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000001C0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000001D0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000001E0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
000001F0  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
```


0x00 is the 'magic bytes' to identify the start of the header. They are always 0x544F4F42 (Alternatively read by IBC2 as 0x424F4F54 due to endianness)

0x48 is a 32bit integer for the kernel image size in little endian.

0x70 is a 32bit integer for the initramfs image size in little endian.


## Booting the kernel
After the kernel image is loaded into memory, IBC2 then looks for the start of the kernel image header. Using the data contained in the header to locate the start of the kernel, the kernel command line, and initramfs image start and end.

It uses these values to create a device tree, and then boots the kernel.



## Known issues/Limitations
ibc2 1.68.17 seems to have an issue loading larger initramfs images.