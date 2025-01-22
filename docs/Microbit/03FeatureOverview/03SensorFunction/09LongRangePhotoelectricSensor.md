# Long-Range Photoelectric Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
<font style="color:rgba(0, 0, 0, 0.85);"></font><font style="color:rgb(13, 13, 13);">The long-range photoelectric sensor is a detection switch based on the infrared reflection principle. Its primary function is to accurately detect the presence of obstacles in front of the sensor. The effective detection range is from 0 to 2 meters. Additionally, the sensor’s parameters can be flexibly adjusted using a potentiometer to accommodate various application scenarios.</font>

## <font style="color:rgb(13, 13, 13);">Specification</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| <font style="color:rgb(13, 13, 13);">Name</font> | <font style="color:rgb(13, 13, 13);">Long-Range Photoelectric Sensor</font> |
| <font style="color:rgb(13, 13, 13);">Number</font> | B0020018 |
| <font style="color:rgb(13, 13, 13);"> Voltage</font> | 5V - DC |
| <font style="color:rgb(13, 13, 13);">Data Type</font> | <font style="color:rgb(13, 13, 13);">Digital Signal</font> |
| <font style="color:rgb(13, 13, 13);">Data Range</font> | 0 or 1 |
| <font style="color:rgb(13, 13, 13);">Interface Type</font> | Grove |
| <font style="color:rgb(13, 13, 13);">Module Size</font> | 62×40 (mm) |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](img/01Long.png) | | |
| :---: | --- | --- |
| ![](img/02Long.png) | ![](img/03Long.png) | ![](img/04Long.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_<font style="color:rgb(13, 13, 13);"> </font> | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Long-range Photoelectric Sensor Connection Diagram</font>** | | |


<font style="color:rgb(13, 13, 13);">The long-range photoelectric sensor can be connected to the P0, P1, P2, P8, P12, or P16 ports on the micro:bit Intelligent Hub. By programming, its status can be monitored. When an obstacle is detected, the sensor outputs a low logic level ("0") and the red indicator light turns on. In the absence of an obstacle, it outputs a high logic level ("1") and the red light is off.</font>



![](img/05Long.gif)

<font style="background-color:rgb(253, 253, 254);"></font>

<font style="color:rgb(13, 13, 13);">The long-range photoelectric sensor features a built-in sensitivity adjustment mechanism. Users can easily adjust sensitivity by turning the potentiometer at the rear. Rotating it clockwise increases the detection range and sensitivity, while counterclockwise rotation decreases the range and sensitivity.</font>

## **<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
![](img/06Long.webp)



<font style="color:rgb(13, 13, 13);">In the MakeCode coding software, the sensor's signal value from the P0 port can be read using the Microbit extension. The data can then be visualized on the micro:bit’s LED matrix.</font>

