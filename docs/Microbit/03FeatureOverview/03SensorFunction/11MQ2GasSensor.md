# MQ-2 Gas Sensor
## Principle  
The <font style="color:rgb(35,31,32);">MQ-2 Gas Sensor</font> uses tin dioxide (SnO2) with low conductivity as the sensitive material. When combustible gases are present in the environment, the sensor's conductivity significantly increases with the concentration of the gas. This sensor is highly sensitive to liquefied gas, propane, and hydrogen, while also performing well in detecting natural gas and other combustible vapors.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgb(35,31,32);">MQ-2 Gas Sensor</font> |
| Code | B0020005 |
| Dimension | <font style="color:rgb(0,0,0);">40×24×12 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V - DC</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |
|  Data Type   | <font style="color:rgb(0,0,0);">Analog Signal  </font> |
|  Data Range   | <font style="color:rgb(0,0,0);">0~1023</font> |




## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| <!-- 这是一张图片，ocr 内容为： -->
![](img/MQ1.png) | | |
| :---: | --- | --- |
| <!-- 这是一张图片，ocr 内容为： -->
![](img/MQ2.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/MQ3.png) | <!-- 这是一张图片，ocr 内容为： -->
![](img/MQ4.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">MQ-2 Gas Sensor Connection Diagram</font>** | | |


<font style="color:rgb(35,31,32);">The combustible gas sensor can be connected to the P0, P1, and P2 interfaces of the micro:bit smart hub. In the coding environment, the analog values of the combustible gas sensor can be read. Its characteristic is that the sensor's output increases with the concentration of combustible gas; conversely, when the gas concentration decreases, the detected value decreases accordingly.  </font>

> **Note: It is normal for the sensor to heat up during use. If overheating occurs, please stop using it immediately to avoid burns.**
>

## <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
<!-- 这是一张图片，ocr 内容为： -->
![](img/MQ5.gif)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, the sensor signal value from the P0 port can be read using the micro:bit extension. The data can then be visualized on the micro:bit's LED matrix. </font>

