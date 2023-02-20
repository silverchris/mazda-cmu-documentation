- [VIP](#vip)
  - [Messages](#messages)
    - [Message ID Table](#message-id-table)
      - [GPIO Event (0x0C0)](#gpio-event-0x0c0)
      - [GPIO Event (0x0E0)](#gpio-event-0x0e0)
      - [GPIO Event (0x0E1)](#gpio-event-0x0e1)
      - [GPIO Event (0x0E2)](#gpio-event-0x0e2)
    - [Message format](#message-format)
    - [Checksum calculation](#checksum-calculation)
    - [Key message](#key-message)
  - [Kernel Modules](#kernel-modules)
    - [com.jci.cpp.drivers.GpioChip.ko](#comjcicppdriversgpiochipko)
    - [cmu\_io.ko](#cmu_ioko)
    - [VIP CPU](#vip-cpu)
    - [CAN BUS IDs](#can-bus-ids)

# VIP

[Renaesas R5F35MCEJFB](doc/assets/R5F35MCEJFB.pdf)

Implements the communication between the main processor and the CAN/LIN busses.

Also performs watchdog function, and will reset the main processor if communication is disrupted. (handled by vim_app)

SPI speed: 4Mhz

SPI mode: 3 (SPI CPHA=1 SPI CPOL = 1)

SPI bits per word: 8

Device: /dev/spidev1.0




## Messages

### Message ID Table

| ID    | Message                                               | Sender         |
|-------|-------------------------------------------------------|----------------|
| 0x002 | Communications Established                            | VIP CMU        |
| 0x030 | Heart Beat                                            | CMU            |
| 0x031 | Heart Beat Request                                    | VIP            |
| 0x037 | VIP Self Reset                                        | VIP            |
| 0x039 |                                                       | VIP            |
| 0x03B |                                                       | VIP            |
| 0x03C |                                                       | VIP            |
| 0x03D |                                                       | VIP            |
| 0x03E |                                                       | VIP            |
| 0x03F |                                                       | VIP            |
| 0x043 | Power Hold                                            | CMU            |
| 0x048 | Emergency                                             | CMU            |
| 0x04A | MIC Power                                             | CMU            |
| 0x04B | Camera Power                                          | CMU            |
| 0x050 | Normal Mode                                           | CMU            |
| 0x051 | Power Down Ready                                      | CMU            |
| 0x081 | ATOD or Batt Monitor                                  | VIP            |
| 0x083 | ATOD or Batt Monitor                                  | VIP            |
| 0x084 | Mouseapp Encoder1 CW                                  | VIP            |
| 0x085 | Mouseapp Encoder1 CCW                                 | VIP            |
| 0x086 | KEYAPP Encoder2 CW                                    | VIP            |
| 0x087 | KEYAPP Encoder2 CCW                                   | VIP            |
| 0x088 | KEYAPP Invalid                                        | VIP            |
| 0x089 | KEYAPP Invalid                                        | VIP            |
| 0x08A | KEYAPP All Buttons Released                           | VIP            |
| 0x08B | KEYAPP SW1 Button1 Pressed                            | VIP            |
| 0x08C | KEYAPP SW1 Button2 Pressed                            | VIP            |
| 0x08D | KEYAPP SW1 Button3 Pressed                            | VIP            |
| 0x08E | KEYAPP SW1 Button4 Pressed                            | VIP            |
| 0x08F | KEYAPP SW1 Button5 Pressed                            | VIP            |
| 0x090 | KEYAPP SW1 Button6 Pressed                            | VIP            |
| 0x091 | KEYAPP SW1 Button7 Pressed                            | VIP            |
| 0x092 | KEYAPP SW1 Button8 Pressed                            | VIP            |
| 0x093 | KEYAPP SW1 Button9 Pressed                            | VIP            |
| 0x094 | KEYAPP SW1 Button10 Pressed                           | VIP            |
| 0x095 | KEYAPP SW1 Short to Ground                            | VIP            |
| 0x096 | KEYAPP SW1 Short to Ground                            | VIP            |
| 0x097 | KEYAPP SW1 Open                                       | VIP            |
| 0x098 | KEYAPP SW2 Button1 Pressed                            | VIP            |
| 0x099 | KEYAPP SW2 Button2 Pressed                            | VIP            |
| 0x09A | KEYAPP SW2 Button3 Pressed                            | VIP            |
| 0x09B | KEYAPP SW2 Button4 Pressed                            | VIP            |
| 0x09C | KEYAPP SW2 Button5 Pressed                            | VIP            |
| 0x09D | KEYAPP SW2 Button6 Pressed                            | VIP            |
| 0x09E | KEYAPP SW2 Button7 Pressed                            | VIP            |
| 0x09F | KEYAPP SW2 Button8 Pressed                            | VIP            |
| 0x0A0 | KEYAPP SW2 Button9 Pressed                            | VIP            |
| 0x0A1 | KEYAPP SW2 Button10 Pressed                           | VIP            |
| 0x0A2 | KEYAPP SW2 Short to Ground                            | VIP            |
| 0x0A3 | KEYAPP SW2 Short to Ground                            | VIP            |
| 0x0A4 | KEYAPP SW2 Open                                       | VIP            |
| 0x0A5 | KEYAPP SW3 Button1 Pressed                            | VIP            |
| 0x0A6 | KEYAPP SW3 Button2 Pressed                            | VIP            |
| 0x0A7 | KEYAPP SW3 Button3 Pressed                            | VIP            |
| 0x0A8 | KEYAPP SW3 Button4 Pressed                            | VIP            |
| 0x0A9 | KEYAPP SW3 Button5 Pressed                            | VIP            |
| 0x0AA | KEYAPP SW3 Button6 Pressed                            | VIP            |
| 0x0AB | KEYAPP SW3 Button7 Pressed                            | VIP            |
| 0x0AC | KEYAPP SW3 Button8 Pressed                            | VIP            |
| 0x0AD | KEYAPP SW3 Button9 Pressed                            | VIP            |
| 0x0AE | KEYAPP SW3 Button10 Pressed                           | VIP            |
| 0x0AF | KEYAPP SW3 Short to Ground                            | VIP            |
| 0x0B0 | KEYAPP SW3 Short to Ground                            | VIP            |
| 0x0B1 | KEYAPP SW3 Open                                       | VIP            |
| 0x0B2 | KEYAPP SW4 Button1 Pressed                            | VIP            |
| 0x0B3 | KEYAPP SW4 Button2 Pressed                            | VIP            |
| 0x0B4 | KEYAPP SW4 Button3 Pressed                            | VIP            |
| 0x0B5 | KEYAPP SW4 Button4 Pressed                            | VIP            |
| 0x0B6 | KEYAPP SW4 Button5 Pressed                            | VIP            |
| 0x0B7 | KEYAPP SW4 Button6 Pressed                            | VIP            |
| 0x0B8 | KEYAPP SW4 Button7 Pressed                            | VIP            |
| 0x0B9 | KEYAPP SW4 Button8 Pressed                            | VIP            |
| 0x0BA | KEYAPP SW4 Button9 Pressed                            | VIP            |
| 0x0BB | KEYAPP SW4 Button10 Pressed                           | VIP            |
| 0x0BC | KEYAPP SW4 Short to Ground                            | VIP            |
| 0x0BD | KEYAPP SW4 Short to Ground                            | VIP            |
| 0x0BE | KEYAPP SW4 Open                                       | VIP            |
| 0x0BF | KEYAPP Max                                            | VIP            |
| 0x0C0 | [GPIO Event (0x0C0)](#gpio-event-0x0c0)               | VIP            |
| 0x0C1 | ACK  (Message length is always 3)                     | VIP            |
| 0x0C2 | NACK (Message length is always 3)                     | VIP            |
| 0x0e0 | [GPIO Event (CAN_Day_Mode)](#gpio-event-0x0e0)        | VIP            |
| 0x0e1 | [GPIO Event (Safe_Shutdown](#gpio-event-0x0e1)        | VIP            |
| 0x0e2 | [GPIO Event (Can_Ignition_Status)](#gpio-event-0x0e1) | VIP            |
| 0x100 | Wheel Speed                                           | VIP            |
| 0x116 | Yaw Rate                                              | VIP            |
| 0x118 | Reverse Lamp                                          | VIP            |
| 0x11E |                                                       | VIP            |
| 0x140 |                                                       | VIP            |
| 0x144 | VBS Ready                                             | VIP            |
| 0x180 |                                                       | VIP            |
| 0x1C0 |                                                       | VIP            |
| 0x144 | VBS Ready                                             |                |
| 0x160 | SPI Ready                                             | vim_app -> vbs |

#### GPIO Event (0x0C0)

| Byte | GPIO Event        |
|------|-------------------|
| 0    | Mic Power Good    |
| 1    | Camera Power Good |
| 2    | USB Power Good    |
| 3    | Reverse           |
| 6    | DO_USB_PWR_EN     |
| 7    | Can Inhibit Sense |

#### GPIO Event (0x0E0)

| Byte | GPIO Event   |
|------|--------------|
| 0    | CAN_Day_Mode |

#### GPIO Event (0x0E1)

| Byte | GPIO Event    |
|------|---------------|
| 0    | Safe_Shutdown |

#### GPIO Event (0x0E2)

| Byte | GPIO Event          |
|------|---------------------|
| 0    | CAN_Ignition_Status |


### Message format
20 bytes long

First two bytes are message id

Third byte is length


Last byte is checksum

### Checksum calculation
```C
    unsigned int checksum = 0;
    for (int x = 0; x < 19; x += 1) {
		checksum = msg[x] + checksum;
    }
```


### Key message
First two bytes message id

3rd = 0 for release 1 for pressed


## Kernel Modules

### com.jci.cpp.drivers.GpioChip.ko
Looks to emulate a GpioChip. Doesn't actually interact with hardware, just reacts to userspace reads and writes to it's exported GPIO pins at /sys/class/gpio/gpiochip224

### cmu_io.ko
Provides VIP interrupt(GPIO2_IO10) to vim_app through /dev/cmu_io


### VIP CPU
Running Renasas MR30 RTOS

1 Cyclic task
21 normal tasks


### CAN BUS IDs

Below is a list of all known CAN bus Message IDs that the VIP is listening for.

The `PRIVATE` bus is used for communication between the CMU, CD player, TAU

The `PUBLIC` bus is used to communcate with the rest of the car

| INDEX | BUS     | CAN Message ID |
|-------|---------|----------------|
| 000   | PRIVATE | 0x470          |
| 001   | PRIVATE | 0x452          |
| 002   | PRIVATE | 0x451          |
| 003   | PRIVATE | 0x450          |
| 004   | PRIVATE | 0x425          |
| 005   | PRIVATE | 0x424          |
| 006   | PRIVATE | 0x423          |
| 007   | PRIVATE | 0x422          |
| 008   | PRIVATE | 0x421          |
| 009   | PRIVATE | 0x41b          |
| 010   | PRIVATE | 0x41a          |
| 011   | PRIVATE | 0x419          |
| 012   | PRIVATE | 0x418          |
| 013   | PRIVATE | 0x417          |
| 014   | PRIVATE | 0x416          |
| 015   | PRIVATE | 0x415          |
| 016   | PRIVATE | 0x414          |
| 017   | PRIVATE | 0x412          |
| 018   | PRIVATE | 0x411          |
| 019   | PRIVATE | 0x410          |
| 020   | PRIVATE | 0x310          |
| 021   | PRIVATE | 0x397          |
| 022   | PRIVATE | 0x393          |
| 023   | PRIVATE | 0x392          |
| 024   | PRIVATE | 0x391          |
| 025   | PRIVATE | 0x390          |
| 026   | PRIVATE | 0x38C          |
| 027   | PRIVATE | 0x38B          |
| 028   | PRIVATE | 0x381          |
| 029   | PRIVATE | 0x380          |
| 030   | PRIVATE | 0x37C          |
| 031   | PRIVATE | 0x379          |
| 032   | PRIVATE | 0x370          |
| 033   | PRIVATE | 0x36E          |
| 034   | PRIVATE | 0x36D          |
| 035   | PRIVATE | 0x36C          |
| 036   | PRIVATE | 0x36B          |
| 037   | PRIVATE | 0x36A          |
| 038   | PRIVATE | 0x366          |
| 039   | PRIVATE | 0x365          |
| 040   | PRIVATE | 0x364          |
| 041   | PRIVATE | 0x363          |
| 042   | PRIVATE | 0x362          |
| 043   | PRIVATE | 0x361          |
| 044   | PRIVATE | 0x351          |
| 045   | PRIVATE | 0x116          |
| 046   | PRIVATE | 0x115          |
| 048   | PUBLIC  | 0x4FE          |
| 049   | PUBLIC  | 0x4FD          |
| 050   | PUBLIC  | 0x4FB          |
| 051   | PUBLIC  | 0x4FA          |
| 052   | PUBLIC  | 0x4F7          |
| 053   | PUBLIC  | 0x4F3          |
| 054   | PUBLIC  | 0x4F0          |
| 055   | PUBLIC  | 0x4E0          |
| 056   | PUBLIC  | 0x4DE          |
| 057   | PUBLIC  | 0x4DC          |
| 058   | PUBLIC  | 0x4DB          |
| 059   | PUBLIC  | 0x4DA          |
| 060   | PUBLIC  | 0x4D9          |
| 061   | PUBLIC  | 0x4D8          |
| 062   | PUBLIC  | 0x4D7          |
| 063   | PUBLIC  | 0x4D6          |
| 064   | PUBLIC  | 0x4D5          |
| 065   | PUBLIC  | 0x4D4          |
| 066   | PUBLIC  | 0x4D3          |
| 067   | PUBLIC  | 0x4D2          |
| 068   | PUBLIC  | 0x4D1          |
| 069   | PUBLIC  | 0x4D0          |
| 070   | PUBLIC  | 0x4CA          |
| 071   | PUBLIC  | 0x49C          |
| 072   | PUBLIC  | 0x49B          |
| 073   | PUBLIC  | 0x499          |
| 074   | PUBLIC  | 0x498          |
| 075   | PUBLIC  | 0x495          |
| 076   | PUBLIC  | 0x494          |
| 077   | PUBLIC  | 0x492          |
| 078   | PUBLIC  | 0x491          |
| 079   | PUBLIC  | 0x48E          |
| 080   | PUBLIC  | 0x48D          |
| 081   | PUBLIC  | 0x48B          |
| 082   | PUBLIC  | 0x48A          |
| 083   | PUBLIC  | 0x488          |
| 084   | PUBLIC  | 0x487          |
| 085   | PUBLIC  | 0x485          |
| 086   | PUBLIC  | 0x484          |
| 087   | PUBLIC  | 0x482          |
| 088   | PUBLIC  | 0x481          |
| 089   | PUBLIC  | 0x47B          |
| 090   | PUBLIC  | 0x477          |
| 091   | PUBLIC  | 0x445          |
| 092   | PUBLIC  | 0x43E          |
| 093   | PUBLIC  | 0x43B          |
| 094   | PUBLIC  | 0x436          |
| 095   | PUBLIC  | 0x42E          |
| 096   | PUBLIC  | 0x425          |
| 097   | PUBLIC  | 0x420          |
| 098   | PUBLIC  | 0x415          |
| 099   | PUBLIC  | 0x40a          |
| 100   | PUBLIC  | 0x35f          |
| 101   | PUBLIC  | 0x340          |
| 102   | PUBLIC  | 0x274          |
| 103   | PUBLIC  | 0x25d          |
| 104   | PUBLIC  | 0x24b          |
| 105   | PUBLIC  | 0x24a          |
| 106   | PUBLIC  | 0x249          |
| 107   | PUBLIC  | 0x240          |
| 108   | PUBLIC  | 0x228          |
| 109   | PUBLIC  | 0x21d          |
| 110   | PUBLIC  | 0x21c          |
| 111   | PUBLIC  | 0x21b          |
| 112   | PUBLIC  | 0x215          |
| 113   | PUBLIC  | 0x211          |
| 114   | PUBLIC  | 0x20a          |
| 115   | PUBLIC  | 0x202          |
| 116   | PUBLIC  | 0x165          |
| 117   | PUBLIC  | 0x130          |
| 118   | PUBLIC  | 0x0fd          |
| 119   | PUBLIC  | 0x09F          |
| 120   | PUBLIC  | 0x09E          |
| 121   | PUBLIC  | 0x09B          |
| 122   | PUBLIC  | 0x09A          |
| 123   | PUBLIC  | 0x08a          |
| 124   | PUBLIC  | 0x086          |
| 125   | PUBLIC  | 0x079          |
| 126   | PUBLIC  | 0x078          |
| 127   | PUBLIC  | 0x7EA          |
| 128   | PUBLIC  | 0x7E9          |
| 129   | PUBLIC  | 0x7E8          |
| 130   | PUBLIC  | 0x7DF          |
| 131   | PUBLIC  | 0x7CF          |
| 132   | PUBLIC  | 0x7CC          |
| 133   | PUBLIC  | 0x7BF          |
| 134   | PUBLIC  | 0x7B8          |
| 135   | PUBLIC  | 0x7AC          |
| 136   | PUBLIC  | 0x7A8          |
| 137   | PUBLIC  | 0x79B          |
| 138   | PUBLIC  | 0x784          |
| 139   | PUBLIC  | 0x76C          |
| 140   | PUBLIC  | 0x769          |
| 141   | PUBLIC  | 0x768          |
| 142   | PUBLIC  | 0x74E          |
| 143   | PUBLIC  | 0x74C          |
| 144   | PUBLIC  | 0x73F          |
| 145   | PUBLIC  | 0x73C          |
| 146   | PUBLIC  | 0x73B          |
| 147   | PUBLIC  | 0x739          |
| 148   | PUBLIC  | 0x738          |
| 149   | PUBLIC  | 0x72F          |
| 150   | PUBLIC  | 0x72E          |
| 151   | PUBLIC  | 0x728          |
| 152   | PUBLIC  | 0x71E          |
| 153   | PUBLIC  | 0x70E          |