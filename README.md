# 0xcb-1337
## Mechanical macropad with OLED running QMK

![](https://github.com/Conor-Burns/0xcb-1337/blob/main/LICENSE.svg)

### VIA

[src/0xcb/1337/1337.json](https://github.com/Conor-Burns/keyboards/tree/0xcb-1337/src/0xcb/1337)

### QMK

[keyboards/0xcb/1337/](https://github.com/Conor-Burns/qmk_firmware/tree/0xcb-1337/keyboards/0xcb/1337)

#### Flashing

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* `export CONFIG_USB_ACM=y`
* Press switch 1 while plugging in to go into dfu mode
* `make 0xcb/1337:via:flash`

### PCB:
Import .json to EasyEDA to edit the source

[Schematic](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/rev1.1/Schematic_1337.pdf)

![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/top.png)

![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/bottom.png)


#### BOM:
|Name              |Designator   |Qty.|Supplier |LCSC Nb.|
|------------------|-------------|----|---------|--------|
|Pro Micro - 5V    |MCU          |1   |Amazon   |        |
|OLED 128X64       |U1           |1   |Amazon   |        |
|CHERRY MX LED 1.0U|SW1,...,SW9  |9   |Any mx sw|        |
|9926A N-CH Mosfet |P1           |1   |LCSC     |C85679  |
|10K Resistor      |R1           |1   |LCSC     |C15401  |
|WS2812B RGB LED   |RGB1,...,RGB4|4   |LCSC     |C527089 |
|EC11 Encoder      |ENC1         |1   |LCSC     |C470793 |
|100nF Capacitor   |C1,...,C4    |4   |LCSC     |C24452  |
|LED Resistor 330  |R2,...,R11   |10  |LCSC     |C380892 |
