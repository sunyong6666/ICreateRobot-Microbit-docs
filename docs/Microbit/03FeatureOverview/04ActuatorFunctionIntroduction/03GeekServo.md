# Geek Servo
## Introduction  
<font style="color:rgba(0, 0, 0, 0.85);">The Geek Servo module can control rotation to precise angles, making it suitable for control systems where the angle needs to change continuously and be maintained. It is compatible with LEGO structural components, with a standard LEGO cross axle for the output shaft. It is primarily used for controlling movement in joints.</font>

## Specifications  
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | --- |
| <font style="color:rgb(13, 13, 13);">Name</font> | <font style="color:rgba(0, 0, 0, 0.85);">Geek Servo</font> |
| Code | <font style="color:rgba(0, 0, 0, 0.85);">Y0080070016</font> |
| <font style="color:rgb(13, 13, 13);">Voltage</font> | <font style="color:rgba(0, 0, 0, 0.85);">5V－DC</font> |
| <font style="color:rgba(0, 0, 0, 0.85);"> Dimensions  </font> | <font style="color:rgba(0, 0, 0, 0.85);">40×24×24 mm</font> |
| <font style="color:rgba(0, 0, 0, 0.85);">Control Signal  </font> | <font style="color:rgba(0, 0, 0, 0.85);"> PWM Signal  </font> |
| <font style="color:rgba(0, 0, 0, 0.85);">Rated Current  </font> | <font style="color:rgba(0, 0, 0, 0.85);">200 mA</font> |
| <font style="color:rgba(0, 0, 0, 0.85);">Stall Current  </font> | <font style="color:rgba(0, 0, 0, 0.85);">700 mA</font> |
| <font style="color:rgba(0, 0, 0, 0.85);">Maximum Torque  </font> | <font style="color:rgba(0, 0, 0, 0.85);">500 N·cm</font> |
| <font style="color:rgba(0, 0, 0, 0.85);">Angle Range  </font> | <font style="color:rgba(0, 0, 0, 0.85);">0°~ 300°</font> |
| <font style="color:rgba(0, 0, 0, 0.85);">Interface Type  </font> | 3P - 2.54 mm Dupont Header (Orange is signal S, Red is positive +, Gray is negative -)   |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](img/GeekServo01.png) | | |
| :---: | --- | --- |
| ![]((img/GeekServo02.png) | ![](img/GeekServo03.png) | ![](img/GeekServo04.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Geek Servo Connection Diagram</font>** | | |


<font style="color:rgb(0,0,0);">The Geek Servo can be connected to the micro:bit smart hub's interfaces: S1, S2, S3, and S4. The servo can control movements within a range of 0° to 300°.  </font>

> **Note**: When using the servo module, avoid stalling to prevent damage to the servo.
>

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/GeekServo05.webp)

In the MakeCode coding software, by adding the  micro:bit extension, you can program the servo module to move as follows:

+ <font style="color:rgb(0,0,0);">When button A is pressed, the Geek Servo will move to 300°.</font>
+ <font style="color:rgb(0,0,0);">When button B is pressed, the Geek Servo will move to 150°.</font>

