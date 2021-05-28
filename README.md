# 0xcb-1337
## Mechanical macropad with OLED running QMK

Licence | OSHWA | Tindie
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/Conor-Burns/0xcb-1337/blob/main/IMG/LICENSE.svg) | [![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/rev3.0/OSHWA.svg)](https://certification.oshwa.org/de000113.html) | <a href="https://www.tindie.com/stores/0xcb/?ref=offsite_badges&utm_source=sellers_conorlburns&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>

### VIA

[src/0xcb/1337/1337.json](https://github.com/Conor-Burns/keyboards/tree/0xcb-1337/src/0xcb/1337)

### QMK

[keyboards/0xcb/1337/](https://github.com/Conor-Burns/qmk_firmware/tree/0xcb-1337/keyboards/0xcb/1337)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* Press switch 1 while plugging in to go into dfu mode (or reset)
* `make 0xcb/1337:via:flash`

### PCB:
KiCad 5.99
[Schematic](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/rev3.0/Schematic_1337.pdf)

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/rev3.0/top.png)  |  ![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/rev3.0/bottom.png)

#### BOM:
|Qty|Reference(s)                                                                |Value                           |Part Nb.             |Alt Part Nb.|
|---|----------------------------------------------------------------------------|--------------------------------|---------------------|------------|
|17 |C1, C2, C3, C6, C7, C8, C9, C10, C13, C14, C21, C22, C23, C24, C25, C26, C27|100n                            |478-5266-1-ND        |C91183      |
|5  |C4, C5, C11, C12, C20                                                       |1u                              |1276-1102-1-ND       |C393692     |
|1  |C15                                                                         |10u                             |587-3383-1-ND        |C441753     |
|4  |C16, C17, C18, C19                                                          |22p                             |478-1167-1-ND        |C85969      |
|4  |D1, D2, D3, D4                                                              |WS2812B                         |1568-COM-16347CT-ND  |C114586     |
|1  |F1                                                                          |1A                              |507-1815-1-ND        |C369150     |
|1  |F2                                                                          |500mA                           |507-1813-1-ND        |C883103     |
|3  |FB1, FB2, FB3                                                               |600R                            |732-1593-1-ND        |C74330      |
|1  |J1                                                                          |USB_IN                          |900-2169900002CT-ND  |C223906     |
|1  |J3                                                                          |USB_OUT                         |900-2169900002CT-ND  |C223906     |
|1  |Q1                                                                          |FDS9926A                        |FDS9926ACT-ND        |C693202     |
|2  |R2, R3                                                                      |5.1k                            |P5.1KDBCT-ND         |C23186      |
|2  |R5, R6                                                                      |22                              |A130081CT-ND         |C174301     |
|6  |R7, R9, R11, R12, R14, R28                                                  |10k                             |RHM10KADCT-ND        |C25804      |
|1  |R13                                                                         |649                             |P649DBCT-ND          |C705928     |
|10 |R15, R16, R17, R18, R19, R20, R21, R22, R23, R29                            |330                             |A130532CT-ND         |C104763     |
|2  |RN1, RN2                                                                    |10k                             |MNR14103RTR-ND       |C109324     |
|1  |SW1                                                                         |SW_Push                         |EG2531CT-ND          |C318884     |
|1  |U1                                                                          |CY7C65634-28LTXCT (or CY7C65632)|428-3154-1-ND        |C1521581    |
|2  |U2, U4                                                                      |USBLC6-2SC6                     |497-5235-1-ND        |C7519       |
|1  |U3                                                                          |ATMEGA32U4                      |ATMEGA32U4RC-MURCT-ND|C112161     |
|1  |Y1                                                                          |12MHz                           |XC2874CT-ND          |C9002       |
|1  |Y2                                                                          |16MHz                           |XC2060CT-ND          |C389842     |
