# Recording Module
## Introduction  
The <font style="color:rgb(0,0,0);">Recording Module</font> is mainly used to capture sound signals from the surrounding environment and convert them into digital signals for storage, allowing for later playback or transmission. It functions as a core component of a small recording device, capable of recording voices, music, environmental sound effects, and more. This module also comes with 5 built-in sound samples, making it easy to create projects.  

## Specifications  
| Item | <font style="color:rgb(0,0,0);">Specification  </font> |
| :---: | :---: |
| Name | <font style="color:rgb(0,0,0);">Recording Module</font> |
| Code | <font style="color:rgb(0,0,0);">B0020030</font> |
| <font style="color:rgb(0,0,0);">Dimension</font> | <font style="color:rgb(0,0,0);">66×40×12 mm</font> |
| Voltage | <font style="color:rgb(0,0,0);">5V－DC</font> |
| Control Signal   | I²C |
| <font style="color:rgb(0,0,0);"></font><font style="color:rgb(13, 13, 13);">Ports</font> | <font style="color:rgba(0, 0, 0, 0.85);">Grove</font> |


## **<font style="color:rgb(13, 13, 13);">Usage</font>**
![](img/RM01.png)

| No.   | Item |  Function   |
| :---: | :---: | :---: |
| ① | Play  |  Plays the currently selected sound effect   |
| ② |    Record   |  Press and hold to start recording   |
| ③ | Switch Button   | Switches to select sound effects   |
| ④ |  Microphone   | <font style="color:rgba(0, 0, 0, 0.85);"> Captures sound  </font> |


<font style="background-color:rgb(253, 253, 254);">Connect the recording module to any Grove Cable on the micro:bit smart hub. The recording module is equipped with internal storage space to store 5 built-in sound effects. By using the record button, users can easily record an audio clip of up to 30 seconds. Even when powered only by the hub, users can operate the module to record and play sounds with the press of a button.  </font>

**5 Built-in Sound Effects**<font style="background-color:rgb(253, 253, 254);">: Machine gun fire, laser firing, racing acceleration, war start, countdown.  </font>



| ![]img/RM02.png) | | |
| :---: | --- | --- |
| ![](img/RM03.png) | ![](img/RM04.png) | ![](img/RM05.png) |
| _<font style="color:rgb(13, 13, 13);">Side View</font>_ | _<font style="color:rgb(13, 13, 13);">Front View</font>_ | _<font style="color:rgb(13, 13, 13);">Side View</font>_ |
|  Recording Module Connection Diagram   | | |


<font style="color:rgb(0,0,0);">The recording module can be connected to the micro:bit smart hub via the I²C interface and controlled through coding.  </font>



## <font style="color:rgb(0,0,0);">Modular Coding  </font>
![](img/RM06.webp)

<font style="color:rgb(0,0,0);">In the MakeCode coding software, by adding the micro:bit extension, you can program the recording module to play the machine gun sound effect when button A is pressed.  </font>

