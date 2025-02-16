# Electromagnet Module
## Introduction  
<font style="color:rgba(0, 0, 0, 0.85);">An electromagnet is a device that generates magnetism when current flows through it. A conductive coil that matches the power of the core is wound around a magnetic core. When current flows through the coil, it generates a magnetic field, acting like a magnet. The magnetic field disappears when the power is turned off.</font>

## Specifications  
| <font style="color:rgba(0, 0, 0, 0.85);">Item</font> | <font style="color:rgba(0, 0, 0, 0.85);"></font>**<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name   |  Electromagnet Module   |
| Code   | <font style="color:rgba(0, 0, 0, 0.85);">B0020044</font> |
| <font style="color:rgb(0,0,0);">Dimension</font> | <font style="color:rgb(0,0,0);">28×24×12 mm</font> |
| <font style="color:rgba(0, 0, 0, 0.85);"> Voltage  </font> | <font style="color:rgba(0, 0, 0, 0.85);">5V－DC</font> |
| <font style="color:rgba(0, 0, 0, 0.85);"> Signal  </font> | <font style="color:rgba(0, 0, 0, 0.85);"> Digital Signal / Analog Signal  </font> |
| <font style="color:rgba(0, 0, 0, 0.85);"> Maximum Pulling Force  </font> | <font style="color:rgba(0, 0, 0, 0.85);">3KG</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |


## Usage  
| ![](img/El01.png) | | |
| :---: | --- | --- |
| ![](img/El02.png) | ![](img/El03.png) | ![](img/El04.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
|  Electromagnet Module Connection Diagram   | | |


<font style="color:rgb(0,0,0);">The electromagnet module can be connected to the micro:bit smart hub's interfaces: P0, P1, P2, P8, P12, and P16.  </font>

> **Note:** The electromagnet module should not be powered on for more than 30s. It is normal for the module to generate heat during operation. If overheating occurs, stop using it to prevent burns.
>

---

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/El05.webp)

In the MakeCode coding software, by adding the <font style="color:rgb(0,0,0);">micro:bit</font> extension, you can program the electromagnet module as follows:

+ <font style="color:rgba(0, 0, 0, 0.85);">When button A is pressed, the electromagnet generates a magnetic field.</font>
+ <font style="color:rgba(0, 0, 0, 0.85);">When button B is pressed, the electromagnet's magnetic field disappears.  
</font><font style="color:rgba(0, 0, 0, 0.85);">Additionally, you can adjust the electromagnet's magnetic force by using the "+" block.</font>

