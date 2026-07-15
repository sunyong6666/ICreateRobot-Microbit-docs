# Ultrasonic Sensor
## <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Principle</font>**
The Long-Range Photoelectric Sensor is a detection switch designed based on the infrared reflection principle. Its primary function is to accurately detect whether an obstacle is present in front of the sensor, with an effective detection range of 0 to 2 meters. In addition, the sensor is equipped with an adjustable potentiometer, allowing users to flexibly adjust the detection parameters to meet the requirements of various application scenarios.  

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| Name |  Ultrasonic Sensor   |
| Code | B0020012 |
|  Dimensions   | <font style="color:rgb(0,0,0);">47×43 mm</font> |
|  Voltage   | 5V - DC |
| Data Type | Analog Signal |
| Data Range | <font style="color:rgb(0,0,0);">2~400 cm</font> |
| <font style="color:rgb(13, 13, 13);">Ports</font> | Grove |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](img/01ultrasonic.png) | | |
| :---: | --- | --- |
| ![](img/02Potentiometer.png) | ![](img/03ultrasonic.png) | ![](img/04Potentiometer.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |



<font style="color:rgb(0,0,0);">The ultrasonic sensor can be connected to the general-purpose sensor ports of the </font>**micro: bit smart hub**<font style="color:rgb(0,0,0);">, including </font>**P0-P13**<font style="color:rgb(0,0,0);">, </font>**P1-P14**<font style="color:rgb(0,0,0);">, </font>**P2-P15**<font style="color:rgb(0,0,0);">, </font>**P7-P8**<font style="color:rgb(0,0,0);">, </font>**P9-P12**<font style="color:rgb(0,0,0);">, and </font>**P10-P16**<font style="color:rgb(0,0,0);">. It is programmed for distance measurement tasks.  </font>

<font style="color:rgb(0,0,0);">The sensor measures the distance between an object and itself. Once installed in a fixed position, it emits ultrasonic pulses and receives reflected waves to calculate distance based on the time difference. Proper sensor placement is crucial to avoid interference from obstacles. Environmental factors like temperature, humidity, and airflow can affect sensor performance. Additionally, the shape, material, and surface smoothness of the detected object impact wave reflection; flat and hard surfaces reflect sound waves more effectively.</font>

## Modular Coding  
![](img/05ultrasonic.gif)

<font style="color:rgb(0,0,0);"></font>

<font style="color:rgb(0,0,0);">Using the </font>**MakeCode**<font style="color:rgb(0,0,0);"> coding software, the Microbit extension allows for coding to read signal values from ports such as </font>**P0**<font style="color:rgb(0,0,0);"> and </font>**P13**<font style="color:rgb(0,0,0);">. The data can be visualized on the </font>**micro: bit LED matrix display**<font style="color:rgb(0,0,0);">.  </font>

The ultrasonic sensor’s return values can be expressed in three units:

+ **Centimeters (cm)**<font style="color:rgb(0,0,0);">: Measures distance in metric units.</font>
+ **Microseconds (µs)**<font style="color:rgb(0,0,0);">: Indicates the time taken for the ultrasonic wave to travel from emission to reception.</font>
+ **Inches (in)**<font style="color:rgb(0,0,0);">: Represents distance in imperial units.</font>

<font style="color:rgb(0,0,0);">By measuring the echo time, the corresponding distance can be calculated using the speed of sound, enabling precise measurement of the target object.</font>

