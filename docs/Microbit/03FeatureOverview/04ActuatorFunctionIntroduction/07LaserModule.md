# Laser Module
## Introduction  
<font style="color:rgb(35,31,32);">The core component of the laser module is a laser diode, which is a semiconductor device capable of directly converting electrical energy into laser light energy.  
</font><font style="color:rgb(35,31,32);">Compared to traditional light sources, laser characteristics come from its unique emission and generation process: When current flows through the laser diode, electrons undergo transitions under specific conditions to release photons. These photons reflect within the medium, exciting more electron transitions, producing a light amplification effect, and forming a highly concentrated laser.  </font>

## Specifications  
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
|  Name   | <font style="color:rgb(0,0,0);">Laser Module  </font> |
|  Code   | <font style="color:rgb(0,0,0);">B0020004</font> |
| <font style="color:rgb(0,0,0);">Dimension</font> | <font style="color:rgb(0,0,0);">28×24×20 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V－DC</font> |
| Control Signal   | <font style="color:rgb(0,0,0);">Digital Signal / Analog Signal  </font> |
| <font style="color:rgb(0,0,0);">Light Source Wavelength  </font> | <font style="color:rgb(0,0,0);">650 nｍ</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**


| ![](img/L01.png) | | |
| :---: | --- | --- |
| ![](img/L02.png) | ![](img/L03.png) | ![](img/L04.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| Laser Module Connection Diagram   | | |


<font style="color:rgb(0,0,0);">The laser module can be connected to the micro:bit smart hub's interfaces: P0, P1, P2, P8, P12, and P16.  </font>

<font style="color:rgb(0,0,0);">When controlling the laser module with a digital signal, a high input voltage turns the laser module on, while a low input voltage turns it off.  
</font><font style="color:rgb(0,0,0);">When controlling the laser module with an analog signal, the greater the input signal, the brighter the laser module; the smaller the input signal, the dimmer the LED light.  </font>

> **Note:** Do not aim the laser at the eyes during use, as it may cause permanent eye damage!  
>

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/L05.webp)

<font style="color:rgba(0, 0, 0, 0.85);">In the MakeCode coding software, by adding the </font><font style="color:rgb(0,0,0);">micro:bit</font><font style="color:rgba(0, 0, 0, 0.85);"> extension, you can program the laser module to blink, and use the "+" block to adjust the laser's power.  </font>

