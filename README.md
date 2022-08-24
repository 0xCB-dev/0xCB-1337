# 0xcb-1337
## Mechanical macropad with OLED running QMK

Licence | OSHWA
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/LICENSE.svg) | [![](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev4.0/OSHWA.svg)](https://certification.oshwa.org/de000121.html)

### Available here:

[KeebSupply](https://keeb.supply/products/0xcb-1337)

### QMK:

[keyboards/0xcb/1337/](https://github.com/qmk/qmk_firmware/tree/master/keyboards/0xcb/1337)

#### Flashing:

* `qmk clone`
* `cd qmk_firmware`
* `export LTO=Y`
* Press switch 1 while plugging in to go into dfu mode (or the reset button)
* `make 0xcb/1337:via:flash`

### Assembly:

You can use the [humanpnp](https://files.0xcb.dev/0xCB-1337/humanpnp.html) to easily place components.

### PCB:
KiCad 6 stable release - using these [libs](https://github.com/0xCB-dev/0xcb-libs)

[Schematic](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev4.0/1337-v4.0.pdf)

Top | Bottom
:-------------------------:|:-------------------------:
![](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev4.0/1337-v4.0.top.png)  |  ![](https://github.com/0xCB-dev/0xcb-1337/blob/main/rev4.0/1337-v4.0.bottom.png)

### Case 3D files:

[STLs](https://github.com/0xCB-dev/0xcb-1337/tree/main/rev4.0/case/STL)

### PCB 3D files:

[FreeCAD](https://github.com/0xCB-dev/0xcb-1337/tree/main/rev4.0/1337-freecad.FCStd)

[STEP](https://github.com/0xCB-dev/0xcb-1337/tree/main/rev4.0/1337-v4.0.step)

[WRL](https://github.com/0xCB-dev/0xcb-1337/tree/main/rev4.0/1337-v4.0.wrl)


#### BOM:
 References                        | Value        | Quantity | Part Nb.            
-----------------------------------|--------------|----------|---------------------
 C2, C4, C6, C7, C8, C10, C12, C14 | 100n         | 8        | C478888             
 C3, C5, C9                        | 1u           | 3        | C29936              
 C11, C13                          | 22p          | 2        | C85969              
 C1                                | 10u          | 1        | C85713              
 R1, R2                            | 5.1k         | 2        | C23186              
 R3, R4                            | 22           | 2        | C174301             
 R5, R6                            | 10k          | 2        | C98220              
 D1, D2, D3, D4, D5, D6, D7, D8    | SK6812MINI-E | 8        | SK6812MINI-E        
 D10, D11, D12, D13                | WS2812B      | 4        | C114586             
 D9                                | SMF5.0CA     | 1        |  576-SMF5.0CA       
 U2                                | USBLC6-2SC6  | 1        | C7519               
 U3                                | ATMEGA32U4   | 1        | ATMEGA32U4RC-MU-ND  
 Y1                                | 16MHz        | 1        | C389842             
 F1                                | 1A           | 1        | C369150             
 SW1                               | SW_Push      | 1        | C318884             
 FB1, FB2                          | 600R         | 2        | C74330              
 RN1                               | 10k          | 1        | C109324             
 J1                                | USB_IN       | 1        | 900-2169900001CT-ND 
