# Six-Way Color & Grayscale Sensor
## **<font style="color:rgb(13, 13, 13);">Overview</font>**
![](img/01six.png)

<font style="color:rgb(0,0,0);">The six-way color grayscale sensor uses three pairs of photosensitive elements to sense the color of the surface. It can also assist the robot in line following while sensing the color of the object.</font>

<font style="color:rgb(0,0,0);">This module can output multi-level data, ranging from analog signals representing light intensity, digital ally processed lines and background recognition information. The design not only ensures the user's simple operation, but also gives a high degree of flexibility, which is very suitable for teachers to explain the relevant knowledge and principle of line inspection technology and color recognition according to the teaching needs.</font>

<font style="color:rgb(0,0,0);">In addition, the module is equipped with cutting-edge adaptive learning functions. By intelligently learning and recognizing diverse background and line colors, it can automatically set and optimize the judgment threshold, so as to significantly improve the accuracy and environmental adaptability of the application, and provide users with a more intelligent and efficient use experience.</font>

## <font style="color:rgb(5, 7, 59);background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">Principle </font>**
![](img/02six.png)

### <font style="color:rgb(13, 13, 13);">Color Detection Principle</font>
<font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Each pair of color sensors combines the functions of a photosensitive sensor and an RGB LED, forming a powerful detection unit. In the real world, when we perceive an object as red, it usually indicates that the object reflects more red light and absorbs other colors more effectively. Based on this principle, when red supplemental lighting is used, the higher the object's red color, the stronger its reflection of red light, and the higher the reading of the photosensitive sensor. This mechanism enables us to quantify the object's "red index."</font>

<font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Similarly, by adjusting the color of the supplementary light to cycle between red, green, and blue, and simultaneously recording the readings of the light sensor at each moment, we can accurately calculate the object's "green index" and "blue index," and then infer the overall color of the detected object.</font>

### <font style="color:rgb(13, 13, 13);">Environmental Interference and Detection Error Analysis</font>
<font style="color:rgb(13, 13, 13);">In the physical world, environmental interference and detection errors are common issues. The color sensor's ability to detect the color of an object depends on the intensity of light reflected from the object under the supplemental lighting. However, ambient light can also be captured by the light sensor, introducing errors. Even under the same environmental conditions, two dual-color sensors may produce different readings when detecting the same object due to individual variations.</font>

<font style="color:rgb(13, 13, 13);">To address these issues, we have carefully designed the sensor casing to isolate the detected object from the sensor, effectively shielding it from ambient light interference. Furthermore, we have developed advanced algorithms that record sensor readings with the supplemental lighting on and off, and calculate the difference between the two. By assuming ambient light intensity remains unchanged during this brief period, this method minimizes errors.</font>

## **<font style="color:rgb(13, 13, 13);">Structure</font>**
![](img/03six.png)   

| **<font style="color:rgb(13, 13, 13);">No.</font>** |  Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: | :---: |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Indicator Light</font> | <font style="color:rgb(13, 13, 13);">Lights up when the corresponding probe detects a "black line."</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Learning Button</font> | <font style="color:rgb(13, 13, 13);">Press once to enter learning mode; long press to change device address.</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Reset Button</font> | <font style="color:rgb(13, 13, 13);">Used to reset the sensor.</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Sensor Probes</font> | <font style="color:rgb(13, 13, 13);">The six probes of the Six-Way Color and Grayscale Sensor.</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Supplementary Light</font> | <font style="color:rgb(13, 13, 13);">Supplementary light corresponding to each probe.</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Interface</font> | <font style="color:rgb(13, 13, 13);">HY2.0-4P port for power supply and signal transmission.</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Address Indicator</font> | <font style="color:rgb(13, 13, 13);">Indicates the device address; different colors represent different addresses.</font> |
| ‚ë? | <font style="color:rgb(13, 13, 13);">Type-C Interface</font> | <font style="color:rgb(13, 13, 13);">For power supply and firmware updates.</font> |


## <font style="color:rgb(13, 13, 13);">Specification</font>
| Item | **<font style="color:rgb(13, 13, 13);">Description</font>** |
| :---: | :---: |
| <font style="color:rgb(13, 13, 13);">Name</font> | <font style="color:rgb(0,0,0);">Six-Way Color & Grayscale Sensor</font> |
| Code | <font style="color:rgb(0,0,0);">B0200011</font> |
| <font style="color:rgb(13, 13, 13);"> Voltage</font> | <font style="color:rgb(0,0,0);">5VÔºçDC</font> |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Communication Method</font> | <font style="color:rgb(0,0,0);">I¬≤C </font> |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Detection Range (Grayscale)</font> | <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Analog output (0~255) / Digital output (0 or 1)</font> |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Detection Range (Color)</font> | <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Red, Yellow, Green, Blue, Purple</font> |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Sensor Count</font> | <font style="color:rgb(0,0,0);">6 </font><font style="color:rgb(13, 13, 13);">Channels</font> |
| Ports | Grove  |
| <font style="color:rgb(13, 13, 13);">Dimensions</font> | <font style="color:rgb(0,0,0);">96 √ó 32  (mm)</font> |


<font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">The Six-Way Color and Grayscale Sensor uses I¬≤C communication. Below is the I¬≤C communication address and corresponding indicator light table:</font>

| **<font style="color:rgb(13, 13, 13);">I¬≤C Address</font>** | **<font style="color:rgb(13, 13, 13);">Indicator Light Color</font>** |
| :---: | :---: |
| 0x70 <font style="color:rgb(13, 13, 13);">(default)</font> | <font style="color:rgb(13, 13, 13);">None</font> |
| 0x71 | <font style="color:rgb(13, 13, 13);">White</font> |
| 0x72 | <font style="color:rgb(13, 13, 13);">Cyan</font> |
| 0x73 | <font style="color:rgb(13, 13, 13);">Magenta</font> |
| 0x74 | <font style="color:rgb(13, 13, 13);">Blue</font> |


<font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">When using I¬≤C communication, ensure that all sensor addresses are unique to avoid communication errors.</font>

## **<font style="color:rgb(13, 13, 13);">Usage</font>**
### <font style="color:rgb(13, 13, 13);">Connection Diagram</font>


| ![](img/04six.png) | ![](img/05six.png) | ![](img/06six.png) |
| :---: | :---: | :---: |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_<font style="color:rgb(13, 13, 13);"> </font> | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
| **<font style="color:rgb(13, 13, 13);">Six-Way Color & Grayscale Sensor Connection Diagram</font>** | | |


<font style="color:rgb(13, 13, 13);">The Six-Way Color and Grayscale Sensor uses I¬≤C communication and can be connected to any I¬≤C interface on the micro:bit Intelligent Hub.</font>

### <font style="background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">Learning Button Function</font>**
<font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">Pressing the learning button activates the line-following learning mode. The following steps outline the procedure:</font>

1. <font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">Place the four probes of the sensor on the background of the line-following map, with the sensor positioned 5mm‚Ä?15mm above the surface.</font>
2. <font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">Press the learning button to trigger learning mode.</font>
3. <font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">When the six line-following status LEDs start blinking rapidly, the sensor is in the learning state.</font>
4. <font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">Move the sensor so that each probe observes both the background and the line. This helps the sensor learn the features of the background and the line.</font>
5. <font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">Continue moving the sensor until the LEDs stop blinking (approximately 5 seconds), indicating successful learning.</font>
6. <font style="color:rgb(13, 13, 13);">After learning, the parameters are saved in the sensor's memory and will remain even after powering off.</font>

<font style="background-color:rgb(253, 253, 254);">Through this simple operation process, you can easily set and store the inspection learning parameters for the sensor, so as to ensure its accurate and stable inspection operation in subsequent use.</font>

<font style="background-color:rgb(253, 253, 254);"></font>

> <font style="background-color:rgb(253, 253, 254);">Note: In the process of sensor learning, if the fill light shows a fast flashing state, it is strictly forbidden to directly illuminate the eyes to prevent damage to vision.</font>
>

### <font style="background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">Analog and Digital Output</font>**
<font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">The sensor can output data as either an analog signal (range 0‚Ä?255) or a digital signal (0 or 1) through any port.</font>

<font style="color:rgb(13, 13, 13);">For accurate interpretation of the analog output, environmental light values should be learned in advance. If the sensor is used in a different lighting condition than it was trained in, the readings may vary significantly. It is recommended to perform environment adaptation learning before actual use.</font>

<font style="color:rgb(13, 13, 13);">The digital output function is used to distinguish between a black line and the background. The threshold for determining the line or background depends on the learned values, so it is essential to perform environment-specific learning.</font>

## <font style="color:rgb(0,0,0);"></font>**<font style="color:rgb(13, 13, 13);">Modular Coding</font>**
<font style="color:rgb(13, 13, 13);">Click here to access the </font>[Six-Way Color and Grayscale Sensor extension](https://www.icrobot.com/www/cn/index.html#/file/index?type2=micro%EF%BC%9Abit)<font style="color:rgb(13, 13, 13);">.</font>

### **<font style="color:rgb(13, 13, 13);">Address Selection</font>**
<font style="color:#000000;background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">The sensor has one default I¬≤C slave address and four selectable addresses, which are indicated by different LED colors. When only one sensor is in use, the default address 0 can be used. When multiple sensors are used, each should be assigned a unique address, and the corresponding group number should be selected in the programming interface.</font>

> <font style="color:#000000;background-color:rgb(253, 253, 254);">Note: If more than one sensor is used and the same address is set, the control will be abnormal.</font>
>

**<font style="color:#000000;background-color:rgb(253, 253, 254);"></font>****<font style="color:rgb(13, 13, 13);">I¬≤C Address Switching</font>****<font style="color:#000000;background-color:rgb(253, 253, 254);">Ôº?</font>**

<font style="color:#000000;background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">To switch the device's I¬≤C address, long press the learning button and wait for the address indicator light to change color. Release the button when the desired address is reached.</font>

The following table lists the correspondence between the I¬≤C slave address of the device, the color of the sensor indicator and the group number in the program extension. Please pay attention to the comparison.

| **<font style="color:rgb(13, 13, 13);">I¬≤C Address</font>** | ******<font style="color:rgb(13, 13, 13);">Group Number</font>** | **<font style="color:rgb(13, 13, 13);">Color</font>** |
| :---: | :---: | :---: |
| 0x70<font style="color:rgb(13, 13, 13);"> (Default)</font> | 0<font style="color:rgb(13, 13, 13);"> (Default)</font> | Any |
| 0x71 | 1 | <font style="color:rgb(13, 13, 13);">White</font> |
| 0x72 | 2 | <font style="color:rgb(13, 13, 13);">Cyan</font> |
| 0x73 | 3 | <font style="color:rgb(13, 13, 13);">Magenta</font> |
| 0x74 | 4 | <font style="color:rgb(13, 13, 13);">Blue</font> |


### **<font style="color:rgb(13, 13, 13);">Program Calibration</font>**
![](img/11six.gif)

<font style="color:rgb(13, 13, 13);">When the sensor is installed in a location where direct operation of the learning button is difficult, the sensor can be controlled through a calibration program block. By selecting an address number (0‚Ä?4), the corresponding sensor can be instructed to enter learning mode. For the specific steps of the learning operation, please refer to the button learning function described in the previous section.</font>

### <font style="color:rgb(5, 7, 59);background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">Serial Output</font>**
![](img/07six.gif)

<font style="color:rgb(13, 13, 13);">The serial output block allows users to read the analog values from all six probes of the sensor simultaneously, improving the efficiency and stability of data collection.</font>

> <font style="background-color:rgb(253, 253, 254);"></font><font style="color:rgb(13, 13, 13);">Note: The analog values read are essentially real-time feedback based on the learned results stored in memory, reflecting the current detection environment.</font>
>

### <font style="color:rgb(5, 7, 59);background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">Digital Output Block</font>**
![](img/08six.gif)

**<font style="background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">The color detection block features color recognition capabilities, allowing it to identify the color of a selected probe at a specified address and output a clear logical value ("Yes" or "No"). This module can accurately distinguish five colors: red, yellow, green, blue, and purple.</font>

![](img/09six.gif)

**<font style="color:rgb(13, 13, 13);">Line-Following Detection Block</font>**<font style="background-color:rgb(253, 253, 254);">  
</font><font style="color:rgb(13, 13, 13);">This block accurately differentiates black lines from backgrounds and provides logical outputs (Yes or No) based on the learned environment. Note that the "black line" and "background" recognized by this module are based on learned environmental light conditions. The "black line" represents areas with lower light reflection intensity, while the "background" refers to areas with higher light reflection intensity within the learned detection area.</font>

### **<font style="color:rgb(13, 13, 13);">Analog Output Block</font>**
![](img/10six.gif)

**<font style="background-color:rgb(253, 253, 254);"></font>**<font style="color:rgb(13, 13, 13);">The analog output block converts the reading of a selected probe into an analog signal (0‚Ä?255 range) for output.</font>



<font style="color:rgb(0,0,0);"></font>

