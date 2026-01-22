# Photosensitive Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
The Photosensitive Sensor is a device that converts light signals into electrical signals using a photosensitive element. In this sensor, there is an inverse relationship between the light intensity and the returned value: the stronger the light, the smaller the returned value; the weaker the light, the larger the returned value.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | Photosensitive Sensor |
| Code | B0020013 |
| <font style="color:rgb(0,0,0);">Dimension</font> | <font style="color:rgb(0,0,0);">28×24×12 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V - DC</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |
|  Data Type   | <font style="color:rgb(0,0,0);">Analog Signal  </font> |
|  Data Range   | <font style="color:rgb(0,0,0);">0~1023 (Bright ~ Dark)  </font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| <!-- 这是一张图片，ocr 内容为： -->
![](img/p1.png) | | |
| :---: | --- | --- |
| <!-- 这是一张图片，ocr 内容为： -->
![](img/p2.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/p3.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/p4.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Photosensitive Sensor Connection Diagram</font>** | | |


The photosensitive sensor can be connected to the P0, P1, and P2 interfaces of the micro:bit smart hub. In the coding environment, users can read the analog values from the sensor. Its characteristic is that the stronger the light, the higher the value output by the sensor; conversely, in a darker environment, the sensor's output value decreases.

## <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
<!-- 这是一张图片，ocr 内容为： -->
![](img/p5.gif)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, the sensor signal value from the P0 port can be read using the micro:bit extension. The data can then be visualized on the micro:bit's LED matrix. </font>

