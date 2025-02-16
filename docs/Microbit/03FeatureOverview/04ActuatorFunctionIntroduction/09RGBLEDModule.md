# RGB LED Module
## Introduction  
<font style="background-color:rgb(253, 253, 254);">The RGB LED Module integrates 8 full-color LEDs and uses the WS2812 main control chip to achieve single-wire control. This design allows users to control all LEDs through a single signal pin, offering flexible manipulation. Additionally, by adjusting the RGB values precisely, users can display a wide range of vibrant colors. The brightness of the LED ring can be adjusted from 0 to 255, meeting various lighting needs.  </font>

> <font style="background-color:rgb(253, 253, 254);"></font>**Note:**<font style="background-color:rgb(253, 253, 254);"> Due to the high brightness output of the RGB LED Module, avoid prolonged direct exposure to the light source to prevent eye damage.  </font>
>

## Specifications  
| Item | <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
|  Name   | <font style="color:rgb(0,0,0);"> RGB LED Module  </font> |
| Code | <font style="color:rgb(0,0,0);">B0020041</font> |
| <font style="color:rgb(0,0,0);">Dimension</font> | <font style="color:rgb(0,0,0);">56×24×12 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V－DC</font> |
| <font style="color:rgb(0,0,0);">Control Signal  </font> | <font style="color:rgb(0,0,0);">Digital Signal  </font> |
| <font style="color:rgb(0,0,0);"> Number of LEDs  </font> | <font style="color:rgb(0,0,0);">8  LEDs  </font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |


## Usage  
![](img/RGB01.png)

| ![](img/RGB02.png) | ![](img/RGB03.png) | ![](img/RGB04.png) |
| :---: | :---: | :---: |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
|  RGB LED Module Connection Diagram   | | |


<font style="color:rgb(0,0,0);">The RGB LED Module can be connected to the micro:bit smart hub’s regular sensor interfaces: P0, P1, P2, P8, P12, and P16 for coding control.  </font>

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/RGB05.png)

<font style="color:rgb(0,0,0);">To use the RGB LED Module, first initialize the port. Here, "strip" is the initial variable. Different variables can be set to correspond to different RGB LED modules on different ports. You can also adjust the corresponding brightness of the LED ring (0~255).  </font>

![](img/RGB06.png)

This module has ten preset colors: Red, Orange, Yellow, Green, Blue, Indigo, Violet, Purple, Black, and White. You can input the corresponding RGB values to display the desired color on the LED ring.  

![](img/RGB07.png)

You can input the corresponding RGB values to display the desired color on the LED ring.  

![](img/RGB08.png)

<font style="color:rgb(0,0,0);">In the MakeCode coding software, by adding the micro:bit extension, you can program the RGB LED Module to display red, as shown in the example program.  </font>

