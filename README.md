# 0xcb-1337
## Mechanical macropad with OLED running QMK

Licence | OSHWA | Tindie
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/IMG/LICENSE.svg) | [![](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev3.0/OSHWA.svg)](https://certification.oshwa.org/de000113.html) | <a href="https://www.tindie.com/stores/0xcb/?ref=offsite_badges&utm_source=sellers_conorlburns&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>

### VIA

[src/0xcb/1337/1337.json](https://github.com/0xCB-dev/0xcb-1337/keyboards/tree/0xcb-1337/src/0xcb/1337)

### QMK

[keyboards/0xcb/1337/](https://github.com/0xCB-dev/qmk_firmware/tree/0xcb-1337)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* Press switch 1 while plugging in to go into dfu mode (or the reset button)
* `make 0xcb/1337:via:flash`

### Assembly:

You can use the [humanpnp](https://files.0xcb.dev/0xCB/1337/humanpnp.html) to easily place components.

### PCB:
KiCad 6
[Schematic](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev3.0/Schematic-1337.pdf)

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev3.0/top.png)  |  ![](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev3.0/bottom.png)

#### BOM:
| References                                        | Value                            | Quantity |Part Nb.          |
|---------------------------------------------------|----------------------------------|----------|------------------|
| C1, C2, C3, C6, ..., C10, C13, C14, C21, ..., C27 | 100n                             | 17       |C478888           |
| C4, C5, C11, C12, C20                             | 1u                               | 5        |C29936            |
| C16, C17, C18, C19                                | 22p                              | 4        |C85969            |
| C15                                               | 10u                              | 1        |C85713            |
| R7, R9, R11, R12, R14, R28                        | 10k                              | 6        |C98220            |
| R2, R3                                            | 5.1k                             | 2        |C23186            |
| R5, R6                                            | 22                               | 2        |C174301           |
| R13                                               | 649                              | 1        |C705928           |
| R15, ..., R23, R29                                | 330                              | 10       |C104763           |
| D1, D2, D3, D4                                    | WS2812B                          | 4        |C114586           |
| U1                                                | CY7C65634-28LTXCT (or CY7C65632) | 1        |428-3154-1-ND     |
| U3                                                | ATMEGA32U4                       | 1        |ATMEGA32U4RC-MU-ND|
| U2, U4                                            | USBLC6-2SC6                      | 2        |C7519             |
| Y1                                                | 12MHz                            | 1        |C9002             |
| Y2                                                | 16MHz                            | 1        |C389842           |
| F1                                                | 1A                               | 1        |C369150           |
| F2                                                | 500mA                            | 1        |C883103           |
| SW1                                               | SW_Push                          | 1        |C318884           |
| FB1, FB2, FB3                                     | 600R                             | 3        |C74330            |
| RN1, RN2                                          | 10k                              | 2        |C109324           |
| Q1                                                | FDS9926A                         | 1        |C693202           |
| J1, J3                                            | USB                              | 2        |C168688           |
