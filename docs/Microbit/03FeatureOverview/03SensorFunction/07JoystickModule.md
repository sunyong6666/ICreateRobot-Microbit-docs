# Joystick Module
## Introduction  
<font style="color:rgba(0, 0, 0, 0.85);">The joystick module is a commonly used electronic input device, primarily designed for directional and amplitude control. It consists of a movable joystick and an internal potentiometer. When the joystick is tilted, its position changes the resistance value of the potentiometer.  </font>

## Specifications  
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgba(0, 0, 0, 0.85);">Joystick Module</font> |
| Code | B0020029 |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);">51×24×34 mm</font> |
| <font style="color:rgb(0,0,0);"> Voltage  </font> | <font style="color:rgb(0,0,0);">5V－DC</font> |
|  Control Signal   | I²C |
|  X / Y Axis Detection Range   | -100~100 |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgb(0,0,0);">Grove</font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
![](img/01Rocker.png) 
| ![](img/02Potentiometer.png) | ![](img/03Rocker.png) | ![](img/04Potentiometer.png) |
| :---: | --- | --- |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |


<font style="color:rgba(0, 0, 0, 0.85);">The joystick module can be connected to the </font>**I²C interface**<font style="color:rgba(0, 0, 0, 0.85);"> of the </font>**micro: bit hub**<font style="color:rgba(0, 0, 0, 0.85);">. In the coding environment, the position of the joystick can be read and utilized.  </font>

![](img/05Rocker.gif)

If the joystick module exhibits accuracy deviations, calibration can be performed using tweezers: Short-circuit the calibration pads with tweezers. The indicator light will start flashing, indicating calibration mode. Perform a full **360° rotation** of the joystick. After completing the rotation, remove the tweezers. When the indicator light turns solid, calibration is successful.

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/06Rocker.gif)

Using the **MakeCode** coding software, the Microbit extension allows:

<font style="color:rgb(13, 13, 13);">Reading directional signals from the joystick module through the </font>**I²C port**<font style="color:rgb(13, 13, 13);"> and displaying them on the </font>**micro: bit LED matrix**<font style="color:rgb(13, 13, 13);">.</font>

![](img/07Rocker.gif)

<font style="color:rgb(0,0,0);">Reading positional values from the joystick module through the </font>**I²C port**<font style="color:rgb(0,0,0);"> and writing them to the serial port.  </font>



