# Soil Moisture Sensor
## **<font style="color:rgb(13, 13, 13);">Principle</font>**
<font style="color:rgb(13, 13, 13);">The soil humidity sensor operates based on the impact of soil moisture content on its resistance. In dry soil, the lack of moisture as a conductive medium results in high resistance; in moist soil, water dissolves some of the salts in the soil, forming an electrolyte solution that significantly lowers the soil's resistivity. By applying a certain voltage between two electrodes and monitoring the resulting current changes or directly measuring the resistance changes, the moisture level in the soil can be accurately assessed.</font>

## <font style="color:rgb(13, 13, 13);">Specifications</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| <font style="color:rgb(13, 13, 13);">Name</font> | Soil Humidity Sensor |
| Code | B0020017 |
| <font style="color:rgb(13, 13, 13);"> Voltage</font> | 5V－DC |
| <font style="color:rgb(13, 13, 13);">Data Type</font> | <font style="color:rgb(13, 13, 13);"> Analog Signal</font> |
| <font style="color:rgb(13, 13, 13);">Data Range</font> | 0~1023 |
| <font style="color:rgb(13, 13, 13);">Ports</font> | Grove |
|  Dimensions   | 79×24 (mm) |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
| ![](img/01Soil.png) | | |
| :---: | --- | --- |
| ![](img/02Soil.png) | ![](img/03Soil.png) | ![](img/04Soil.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Soil Humidity Sensor Connection Diagram</font>** | | |


<font style="color:rgb(13, 13, 13);">The soil humidity sensor can be connected to the P0, P1, or P2 ports of the micro: bit Intelligent Hub. In the coding environment, you can read the analog values from the soil humidity sensor. The sensor behaves as follows: the higher the soil moisture, the higher the detected value; conversely, the lower the soil moisture, the lower the detected value.</font>

> **<font style="color:rgb(13, 13, 13);">Note</font>**<font style="color:rgb(13, 13, 13);">: Avoid exposing the components to water to prevent damage to the sensor.</font>
>

## **<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
![](img/05Soil.webp)

<font style="color:rgb(13, 13, 13);">In the MakeCode coding environment, by adding the Microbit extension, you can program the system to read the soil humidity sensor signal from the P0 port and visualize the data on the micro: bit's LED display.</font>

