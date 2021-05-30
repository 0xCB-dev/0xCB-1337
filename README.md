# 0xcb-1337
## Mechanical macropad with OLED running QMK

Licence | OSHWA | Tindie
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/IMG/LICENSE.svg) | [![](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev3.0/OSHWA.svg)](https://certification.oshwa.org/de000113.html) | <a href="https://www.tindie.com/stores/0xcb/?ref=offsite_badges&utm_source=sellers_conorlburns&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>

### VIA

[src/0xcb/1337/1337.json](https://github.com/0xCB-dev/0xcb-1337/keyboards/tree/0xcb-1337/src/0xcb/1337)

### QMK

[keyboards/0xcb/1337/](https://github.com/0xCB-dev/0xcb-1337/qmk_firmware/tree/0xcb-1337/keyboards/0xcb/1337)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* Press switch 1 while plugging in to go into dfu mode (or reset)
* `make 0xcb/1337:via:flash`

### PCB:
KiCad 5.99
[Schematic](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev3.0/Schematic-1337.pdf)

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev3.0/top.png)  |  ![](https://github.com/0xCB-dev/0xcb-1337/blob/main/PCB/rev3.0/bottom.png)

#### BOM:
|Qty|Reference(s)                                        |Value                |Part Nb.          |
|---|----------------------------------------------------|---------------------|------------------|
|17 |C1, C2, C3, C6, C7, C8, C9, C10, C13, C14, C21 - C27|100n                 |C478888           |
|5  |C4, C5, C11, C12, C20                               |1u                   |C29936            |
|1  |C15                                                 |10u                  |C85713            |
|4  |C16, C17, C18, C19                                  |22p                  |C85969            |
|4  |D1, D2, D3, D4                                      |WS2812B              |C114586           |
|1  |F1                                                  |1A                   |C369150           |
|1  |F2                                                  |500mA                |C883103           |
|3  |FB1, FB2, FB3                                       |600R                 |C74330            |
|1  |J1, J3                                              |TYPE-C-31-M-13       |C223906           |
|1  |Q1                                                  |FDS9926A             |C693202           |
|2  |R2, R3                                              |5.1k                 |C23186            |
|2  |R5, R6                                              |22                   |C174301           |
|6  |R7, R9, R11, R12, R14, R28                          |10k                  |C98220            |
|1  |R13                                                 |649                  |C705928           |
|10 |R15, R16, R17, R18, R19, R20, R21, R22, R23, R29    |330                  |C104763           |
|2  |RN1, RN2                                            |10k                  |C109324           |
|1  |SW1                                                 |SW_Push              |C318884           |
|1  |U1                                                  |CY7C65634 / CY7C65632|428-3154-1-ND     |
|2  |U2, U4                                              |USBLC6-2SC6          |C7519             |
|1  |U3                                                  |ATMEGA32U4           |ATMEGA32U4RC-MU-ND|
|1  |Y1                                                  |12MHz                |C9002             |
|1  |Y2                                                  |16MHz                |C389842           |
