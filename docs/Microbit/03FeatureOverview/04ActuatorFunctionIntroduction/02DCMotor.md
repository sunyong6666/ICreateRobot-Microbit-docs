# DC Motor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
The motor is a key component that provides power for various projects. The module is equipped with a universal 2P - 2.54 mm Dupont header for easy circuit connection, simplifying the connection process. Users can easily adjust the motor's speed and direction through simple coding or control methods, enabling precise control of the project.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item  | <font style="color:rgb(0,0,0);"> Specification  </font> |
| :---: | --- |
| <font style="color:rgb(13, 13, 13);">Name</font> | <font style="color:rgb(35,31,32);">DC Motor</font> |
| Code | B0020019 |
| <font style="color:rgb(13, 13, 13);">Voltage</font> | <font style="color:rgb(0,0,0);">5V－DC</font> |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);">56×24×24 mm</font> |
|  Rated Current   | <font style="color:rgb(0,0,0);">100 mA</font> |
| Stall Current   | <font style="color:rgb(0,0,0);">1000 mA</font> |
| <font style="color:rgb(0,0,0);">Maximum Torque  </font> | <font style="color:rgb(0,0,0);">0.2 N·m</font> |
| <font style="color:rgb(0,0,0);">Max Speed  </font> | <font style="color:rgb(0,0,0);">10000 r/min</font> |
| <font style="color:rgb(0,0,0);">Control Signal  </font> | <font style="color:rgb(0,0,0);"> PWM Signal  </font> |
| <font style="color:rgb(0,0,0);">Interface Type  </font> | 2P - 2.54 mm Dupont Header (Reversing the connection will only affect the motor's rotation direction)  <font style="color:rgb(0,0,0);"> </font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](img/DC01.png) | | |
| :---: | --- | --- |
| ![](img/DC02.png) | ![](img/DC03.png) | ![](img/DC04.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">DC Motor Connection Diagram</font>** | | |


<font style="color:rgb(0,0,0);">The motor can be connected to the micro:bit smart hub's 4 motor driver interfaces: M1, M2, M3, and M4.  </font>

> **Note**: Under the same program, the direction of the motor will be affected by the way the hardware is connected. Please ensure that the direction of each motor is the same when connecting.  
>

## <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
![](img/DC05.webp)

In the MakeCode coding software, by adding the  micro:bit extension, you can program the motor module to rotate at full power of -255 when the "A" button is pressed and at full power of 255 when the "B" button is pressed.

