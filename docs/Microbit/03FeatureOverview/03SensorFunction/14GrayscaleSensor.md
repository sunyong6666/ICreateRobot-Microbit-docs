# Grayscale Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
The Grayscale Sensor is equipped with two high-brightness white LEDs and a photosensitive resistor. When the light emitted by the LEDs strikes surfaces with different reflectivity, the intensity of the reflected light will vary. The resistance of the photosensitive resistor changes according to the intensity of the received light, thereby reflecting the grayscale value of the surface being measured.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgb(35,31,32);">Grayscale Sensor</font> |
| Code | B0020007 |
| <font style="color:rgb(0,0,0);">Dimension</font> | <font style="color:rgb(0,0,0);">28×24×12 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V - DC</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |
|  Data Type   | <font style="color:rgb(0,0,0);">Analog Signal  </font> |
|  Data Range   | <font style="color:rgb(0,0,0);">0~1023 (Black ~ White)  </font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| <!-- 这是一张图片，ocr 内容为： -->
![](img/G1.png) | | |
| :---: | --- | --- |
| <!-- 这是一张图片，ocr 内容为： -->
![](img/G2.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/G3.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/G4.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Grayscale Sensor Connection Diagram</font>** | | |


<font style="color:rgb(0,0,0);">The grayscale sensor can be connected to the P0, P1, and P2 interfaces of the micro:bit smart hub. In the coding environment, users can read the analog values of the grayscale sensor. Its characteristic is that the stronger the reflected light, the higher the output value of the grayscale sensor. Conversely, the weaker the reflected light, the smaller the output value of the grayscale sensor.  </font>

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
<!-- 这是一张图片，ocr 内容为： -->
![](img/G5.gif)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, the sensor signal value from the P0 port can be read using the micro:bit extension. The data can then be visualized on the micro:bit's LED matrix. </font>

