# 0xcb-1337
## Mechanical macropad with OLED running QMK

![](https://github.com/Conor-Burns/0xcb-1337/blob/main/LICENSE.svg)

### VIA

[src/0xcb/1337/1337.json](https://github.com/Conor-Burns/0xcb-1337/blob/main/)

### QMK

[keyboards/0xcb/1337/](https://github.com/Conor-Burns/0xcb-1337/blob/main/)

### PCB:
Import .json to EasyEDA to edit the source

[Schematic](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/rev1.1/Schematic_1337.pdf)

![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/top.png)

![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/bottom.png)


### BOM:
|Name              |Designator                             |Quantity|Manufacturer Part|Manufacturer |Supplier             |Supplier Part|
|------------------|---------------------------------------|--------|-----------------|-------------|---------------------|-------------|
|Pro Micro - 5V    |MCU                                    |1       |                 |             |Amazon               |             |
|10K               |R14                                    |1       |0603WAJ0103T5E   |UniOhm       |LCSC                 |C15401       |
|WS2812B           |RGB2,RGB3,RGB4,RGB1                    |4       |WS2812B-Mini     |Worldsemi    |LCSC                 |C527089      |
|EC111012010H      |ENC3                                   |1       |EC111012010H     |ALPS Electric|LCSC                 |C470793      |
|100nF             |C4,C3,C2,C1                            |4       |CL10B104JB8NNNC  |SAMSUNG      |LCSC                 |C24452       |
|OLED 128X64       |U1                                     |1       |                 |             |Amazon               |             |
|LED Resistor 330  |R21,R17,R19,R20,R16,R22,R23,R24,R18,R15|10      |SYLE1206JN330RP  |SANYEAR      |LCSC                 |C380892      |
|CHERRY MX LED 1.0U|SW6,SW5,SW4,SW2,SW1,SW7,SW9,SW8,SW3    |9       |Cherry           |             |Any mx style switches|CH310-ND     |
|9926A             |P1                                     |1       |9926A            |FM           |LCSC                 |C85679       |
