# Temperature Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
The temperature sensor is specifically designed for humid environments. During operation, the sensor converts detected temperature signals into corresponding voltage signals. These voltage signals are then converted into analog signals and transmitted to the main control board for processing.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name | <font style="color:rgb(0,0,0);">Temperature Sensor</font> |
| Code | B0020014 |
| <font style="color:rgb(0,0,0);"> Dimensions  </font> | <font style="color:rgb(0,0,0);">79×24×12 mm</font> |
|  Voltage   | <font style="color:rgb(0,0,0);">5V－DC</font> |
| <font style="color:rgb(13, 13, 13);">Data Type</font> |  Analog<font style="color:rgb(13, 13, 13);"> Signal</font> |
| <font style="color:rgb(13, 13, 13);">Data Range</font> | <font style="color:rgb(0,0,0);">0~1023</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgb(0,0,0);">Grove</font> |




## Usage


| ![](img/01Temperature.png) | | |
| :---: | --- | --- |
| ![](img/02Temperature.png) | ![](img/03Temperature.png) | ![](img/04Temperature.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| <font style="color:rgb(0,0,0);">Temperature Sensor </font>Connection Diagram | | |


The temperature sensor can connect to **P0**, **P1**, or **P2** ports of the **micro:bit hub**. In the coding environment, the analog values of the sensor can be read. Its characteristics include:  

+ **Temperature increase**: The detected temperature value increases as the ambient temperature rises.
+ **Temperature decrease**: The detected temperature value decreases as the ambient temperature drops.

> **Note**: During use, avoid exposing any parts of the sensor other than the detection head to water to prevent damage.  
>

## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/05Temperature.webp)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, by adding the Microbit extension, you can code the system to read the temperature sensor signal from the P0 port and visualize the data on the micro: bit's LED display.</font>

