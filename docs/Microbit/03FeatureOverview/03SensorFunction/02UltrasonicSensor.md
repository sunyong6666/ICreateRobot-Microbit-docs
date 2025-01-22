# Ultrasonic Sensor
## <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Principle</font>**
The ultrasonic sensor is a device widely used for distance measurement and object detection. It primarily consists of a transmission section, a reception section, and a control section. The core component is a piezoelectric crystal, which vibrates rapidly when stimulated by voltage, emitting ultrasonic signals.  

During operation, the sensor first emits a series of high-frequency ultrasonic pulses through its transmission section. These waves reflect back when they encounter an object and are captured by the reception section. The control section then analyzes the received signal and calculates the distance to the object based on the time difference between signal emission and reception.  

 The ultrasonic sensor offers the advantage of non-contact measurement and can operate stably in various environments. It is widely used in fields such as automation equipment, robotics, liquid level detection, and traffic monitoring.  

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
| ![](img/02ultrasonic.png) | ![](img/03ultrasonic.png) | ![](img/04ultrasonic.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| Ultrasonic Sensor Connection Diagram | | |


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

