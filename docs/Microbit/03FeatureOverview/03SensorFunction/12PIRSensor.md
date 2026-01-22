# PIR Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
<font style="color:rgba(0, 0, 0, 0.85);">The PIR Sensor (Passive Infrared  Radiation Sensor) is an electronic component based on the NS612 pyroelectric digital intelligent sensor. It is capable of detecting infrared radiation emitted by moving infrared sources (such as the human body), thereby sensing the presence of the infrared source.  </font>

## Specifications  
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgba(0, 0, 0, 0.85);">PIR Sensor</font> |
| Code | B0020028 |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);">28×24×12 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V－DC</font> |
| <font style="color:rgb(13, 13, 13);">Data Type</font> |  Analog<font style="color:rgb(13, 13, 13);"> Signal</font> |
|  Data Range   | 0 or 1 |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgb(0,0,0);">Grove</font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| <br/><!-- 这是一张图片，ocr 内容为： -->
![](img/PIR1.png) | | |
| :---: | --- | --- |
| <!-- 这是一张图片，ocr 内容为： -->
![](img/PIR2.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/PIR3.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/PIR4.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| <font style="color:rgba(0, 0, 0, 0.85);">PIR Sensor</font> Connection Diagram | | |


The PIR sensor can connect to the **I²C interface** of the **micro:bit hub**. In the coding environment, the sensor values can be read:

+ When the sensor detects a moving infrared source, the blue LED indicator lights up and outputs a signal value of **0**.
+ If no moving infrared source is detected, the blue LED turns off and outputs a signal value of **1**.

<!-- 这是一张图片，ocr 内容为： -->
![](img/PIR5.gif)

The PIR sensor is equipped with a **linear potentiometer** located on the back for fine sensitivity adjustments:

+ Rotate the potentiometer **clockwise** to increase sensitivity and extend the detection range.
+ Rotate it **counterclockwise** to decrease sensitivity and shorten the detection range.

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
<!-- 这是一张图片，ocr 内容为： -->
![](img/PIR6.gif)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, by adding the micro:bit extension, you can code the system to read the PIR sensor signal from the P0 port and visualize the data on the micro:bit's LED display.</font>

