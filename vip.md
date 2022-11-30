SPI speed: 4Mhz
SPI mode: 3
SPI bits per word: 8
"/dev/spidev1.0"


/dev/cmu_io, provided by kernel module cmu_io. Seems to just connect to GPIO2_IO10?


| ID    | Message                     | Sender |
|-------|-----------------------------|--------|
| 0x002 | Communications Established  | VIP    |
| 0x030 | Heart Beat                  | CMU    |
| 0x031 | Heart Beat Request          | VIP    |
| 0x037 | VIP Self Reset              | VIP    |
| 0x039 |                             | VIP    |
| 0x03B |                             | VIP    |
| 0x03C |                             | VIP    |
| 0x03D |                             | VIP    |
| 0x03E |                             | VIP    |
| 0x03F |                             | VIP    |
| 0x081 | ATOD or Batt Monitor        | VIP    |
| 0x083 | ATOD or Batt Monitor        | VIP    |
| 0x084 | Mouseapp Encoder1 CW        | VIP    |
| 0x085 | Mouseapp Encoder1 CCW       | VIP    |
| 0x086 | KEYAPP Encoder2 CW          | VIP    |
| 0x087 | KEYAPP Encoder2 CCW         | VIP    |
| 0x088 | KEYAPP Invalid              | VIP    |
| 0x089 | KEYAPP Invalid              | VIP    |
| 0x08A | KEYAPP All Buttons Released | VIP    |
| 0x08B | KEYAPP SW1 Button1 Pressed  | VIP    |
| 0x08C | KEYAPP SW1 Button2 Pressed  | VIP    |
| 0x08D | KEYAPP SW1 Button3 Pressed  | VIP    |
| 0x08E | KEYAPP SW1 Button4 Pressed  | VIP    |
| 0x08F | KEYAPP SW1 Button5 Pressed  | VIP    |
| 0x090 | KEYAPP SW1 Button6 Pressed  | VIP    |
| 0x091 | KEYAPP SW1 Button7 Pressed  | VIP    |
| 0x092 | KEYAPP SW1 Button8 Pressed  | VIP    |
| 0x093 | KEYAPP SW1 Button9 Pressed  | VIP    |
| 0x094 | KEYAPP SW1 Button10 Pressed | VIP    |
| 0x095 | KEYAPP SW1 Short to Ground  | VIP    |
| 0x096 | KEYAPP SW1 Short to Ground  | VIP    |
| 0x097 | KEYAPP SW1 Open             | VIP    |
| 0x098 | KEYAPP SW2 Button1 Pressed  | VIP    |
| 0x099 | KEYAPP SW2 Button2 Pressed  | VIP    |
| 0x09A | KEYAPP SW2 Button3 Pressed  | VIP    |
| 0x09B | KEYAPP SW2 Button4 Pressed  | VIP    |
| 0x09C | KEYAPP SW2 Button5 Pressed  | VIP    |
| 0x09D | KEYAPP SW2 Button6 Pressed  | VIP    |
| 0x09E | KEYAPP SW2 Button7 Pressed  | VIP    |
| 0x09F | KEYAPP SW2 Button8 Pressed  | VIP    |
| 0x0A0 | KEYAPP SW2 Button9 Pressed  | VIP    |
| 0x0A1 | KEYAPP SW2 Button10 Pressed | VIP    |
| 0x0A2 | KEYAPP SW2 Short to Ground  | VIP    |
| 0x0A3 | KEYAPP SW2 Short to Ground  | VIP    |
| 0x0A4 | KEYAPP SW2 Open             | VIP    |
| 0x0A5 | KEYAPP SW3 Button1 Pressed  | VIP    |
| 0x0A6 | KEYAPP SW3 Button2 Pressed  | VIP    |
| 0x0A7 | KEYAPP SW3 Button3 Pressed  | VIP    |
| 0x0A8 | KEYAPP SW3 Button4 Pressed  | VIP    |
| 0x0A9 | KEYAPP SW3 Button5 Pressed  | VIP    |
| 0x0AA | KEYAPP SW3 Button6 Pressed  | VIP    |
| 0x0AB | KEYAPP SW3 Button7 Pressed  | VIP    |
| 0x0AC | KEYAPP SW3 Button8 Pressed  | VIP    |
| 0x0AD | KEYAPP SW3 Button9 Pressed  | VIP    |
| 0x0AE | KEYAPP SW3 Button10 Pressed | VIP    |
| 0x0AF | KEYAPP SW3 Short to Ground  | VIP    |
| 0x0B0 | KEYAPP SW3 Short to Ground  | VIP    |
| 0x0B1 | KEYAPP SW3 Open             | VIP    |
| 0x0B2 | KEYAPP SW4 Button1 Pressed  | VIP    |
| 0x0B3 | KEYAPP SW4 Button2 Pressed  | VIP    |
| 0x0B4 | KEYAPP SW4 Button3 Pressed  | VIP    |
| 0x0B5 | KEYAPP SW4 Button4 Pressed  | VIP    |
| 0x0B6 | KEYAPP SW4 Button5 Pressed  | VIP    |
| 0x0B7 | KEYAPP SW4 Button6 Pressed  | VIP    |
| 0x0B8 | KEYAPP SW4 Button7 Pressed  | VIP    |
| 0x0B9 | KEYAPP SW4 Button8 Pressed  | VIP    |
| 0x0BA | KEYAPP SW4 Button9 Pressed  | VIP    |
| 0x0BB | KEYAPP SW4 Button10 Pressed | VIP    |
| 0x0BC | KEYAPP SW4 Short to Ground  | VIP    |
| 0x0BD | KEYAPP SW4 Short to Ground  | VIP    |
| 0x0BE | KEYAPP SW4 Open             | VIP    |
| 0x0BF | KEYAPP Max                  | VIP    |
| 0x0C0 | GPIO Event                  | VIP    |
| 0x100 | Wheel Speed                 | VIP    |
| 0x116 | Yaw Rate                    | VIP    |
| 0x118 | Reverse Lamp                | VIP    |
| 0x11E |                             | VIP    |
| 0x140 |                             | VIP    |
| 0x144 | VBS Ready                   | VIP    |
| 0x180 |                             | VIP    |
| 0x1C0 |                             | VIP    |






## Message format
20 bytes long

### First 2 Bytes
0000 00MM MMMM MMMM

M = Message Id

### Key message
First two bytes message id

3rd = 0 for release 1 for pressed