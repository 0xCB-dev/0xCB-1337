# 0xcb-1337
## Mechanical macropad with OLED running QMK

Licence | OSHWA | Tindie
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/Conor-Burns/0xcb-1337/blob/main/IMG/LICENSE.svg) | ![](https://github.com/Conor-Burns/0xcb-1337/blob/main/IMG/OSHWA.svg) | <a href="https://www.tindie.com/stores/0xcb/?ref=offsite_badges&utm_source=sellers_conorlburns&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>

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

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/toppcb.png)  |  ![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/bottompcb.png)
![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/top.png)  |  ![](https://github.com/Conor-Burns/0xcb-1337/blob/main/PCB/bottom.png)




#### BOM:
|Name              |Designator   |Qty.|Supplier |LCSC Nb.|DigiKey Nb.              |
|------------------|-------------|----|---------|--------|-------------------------|
|Pro Micro - 5V    |MCU          |1   |Amazon   |        |1568-1060-ND             |
|OLED SSD1306 0.96"|U1           |1   |Amazon   |        |                         |
|CHERRY MX LED 1.0U|SW1,...,SW9  |9   |Any mx sw|        |CH310-ND                 |
|9926A N-CH Mosfet |P1           |1   |LCSC     |C85679  |FDS9926ACT-ND            |
|10K Resistor      |R1           |1   |LCSC     |C15401  |CR0603-JW-103ELFCT-ND    |
|WS2812B RGB LED   |RGB1,...,RGB4|4   |LCSC     |C527089 |1568-COM-16347CT-ND      |
|EC11 Encoder      |ENC1         |1   |LCSC     |C470793 |118-PEC11H-4215F-S0024-ND|
|100nF Capacitor   |C1,...,C4    |4   |LCSC     |C24452  |1276-1033-1-ND           |
|LED Resistor 330  |R2,...,R11   |10  |LCSC     |C380892 |311-330FRCT-ND           |
