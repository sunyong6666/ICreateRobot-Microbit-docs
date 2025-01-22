# QuickStart

<font style="color:rgb(13, 13, 13);">This tutorial helps you quickly get started with the </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);"> and guides you through application development with a practical example. In this example, we will show how to control the fan and the red LED using button presses.</font>

+ **Press the button**<font style="color:rgb(13, 13, 13);">: The fan starts, and the red LED lights up.</font>
+ **Release the button**<font style="color:rgb(13, 13, 13);">: The fan stops, and the red LED turns off.</font>

## <font style="color:rgb(42, 43, 46);">Hardware Preparation</font>
| ![](img/01QuickStart.png) | ![](img/02QuickStart.png) | ![](img/03QuickStart.png) |
| :---: | :---: | :---: |
| micro: bit Smart Hub x 1 | Button Sensor x 1 | Grove Cables x 3 |
| ![](img/04QuickStart.png) | ![](img/05QuickStart.png) |  |
| Fan Module x1 | Red LED Module x 1 |  |


### <font style="color:rgb(13, 13, 13);">Power on the micro: bit Smart Hub</font>
![](img/06QuickStart.png)![](img/07QuickStart.png)![](img/08QuickStart.png)



<font style="color:rgb(13, 13, 13);">Press and hold the power button to turn on the device. Once powered up, check the battery status. The device has four indicator LEDs representing the following battery levels: 25%, 50%, 75%, and 100%. If only one LED is blinking, it indicates a low battery. In that case, use the micro USB cable to connect the device to a charger for recharging. All four LEDs will be solid when fully charged, indicating that the battery is full.</font>

### <font style="color:rgb(13, 13, 13);">Connect the Potentiometer, Fan, and Red LED Modules to the Smart Hub</font>
<font style="color:rgb(13, 13, 13);">When connecting, ensure that the Grove cables are connected correctly, paying attention to the orientation. These cables are designed to prevent reverse insertion, so ensure that they are fully plugged in with proper contact.</font>

![](img/09QuickStart.png)



<font style="color:rgb(13, 13, 13);">At this point, the hardware </font><font style="color:rgb(42, 43, 46);">Preparation</font><font style="color:rgb(13, 13, 13);"> for the quick start example is complete. Now, let's proceed with coding the </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);">.</font>  


## <font style="color:rgb(26, 26, 26);"></font><font style="color:rgb(13, 13, 13);">Software </font><font style="color:rgb(42, 43, 46);">Preparation</font>
<font style="color:rgb(13, 13, 13);"></font>**<font style="color:rgb(13, 13, 13);">Get the Software</font>**<font style="color:rgb(13, 13, 13);">The </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);"> is based on the micro: bit</font><font style="color:rgb(13, 13, 13);"> core board, and any software supporting micro: bit</font><font style="color:rgb(13, 13, 13);"> can be used for programming. This tutorial uses </font>**<font style="color:rgb(13, 13, 13);">Microsoft MakeCode for micro: bit</font>**<font style="color:rgb(13, 13, 13);">.</font>

### **Get the Software**
<font style="color:rgb(13, 13, 13);">You can use the programming software in two ways: online through the </font>[cloud platform](https://makecode.microbit.org/#editor)<font style="color:rgb(13, 13, 13);">, or by downloading and installing the </font>[offline software](https://makecode.microbit.org/offline-app)<font style="color:rgb(13, 13, 13);">. In this tutorial, we will use the online programming platform.</font>

<font style="color:rgb(13, 13, 13);">Click the link above to access the online programming platform, where you will see the main interface as shown below.</font>



![](img/10QuickStart.png)



### **<font style="color:rgb(13, 13, 13);">Get the Extension</font>**
<font style="color:rgb(13, 13, 13);">The </font>**<font style="color:rgb(13, 13, 13);">MakeCode</font>**<font style="color:rgb(13, 13, 13);"> coding platform has a dedicated </font>**<font style="color:rgb(13, 13, 13);">Microbit extension</font>**<font style="color:rgb(13, 13, 13);"> for the </font>**<font style="color:rgb(13, 13, 13);">micro: bit Smart Hub</font>**<font style="color:rgb(13, 13, 13);">. You can add this extension to both the online and offline versions of the platform. Click </font>[here](https://www.icrobot.com/www/cn/index.html#/file/index?type1=%E8%BD%AF%E4%BB%B6%E8%B5%84%E6%96%99&type2=micro%EF%BC%9Abit)<font style="color:rgb(13, 13, 13);"> to download the latest version of the </font>**<font style="color:rgb(13, 13, 13);">Microbit extension</font>**<font style="color:rgb(13, 13, 13);">, and extract it to your computer.</font>

### **<font style="color:rgb(13, 13, 13);">Add the Extension</font>**
<font style="color:rgb(13, 13, 13);">Follow the steps below to add the </font>**<font style="color:rgb(13, 13, 13);">Microbit extension</font>**<font style="color:rgb(13, 13, 13);"> to the </font>**<font style="color:rgb(13, 13, 13);">MakeCode</font>**<font style="color:rgb(13, 13, 13);"> platform:</font>

**<font style="color:rgb(13, 13, 13);">Step 1:</font>**

![](img/11QuickStart.png)

**<font style="color:rgb(13, 13, 13);">Step 2:</font>**

![](img/12QuickStart.png)

**<font style="color:rgb(13, 13, 13);">Step 3:</font>**

![](img/13QuickStart.png)

**<font style="color:rgb(13, 13, 13);">Step 4:</font>**

![](img/14QuickStart.png)

**<font style="color:rgb(13, 13, 13);">Step 5:</font>**

![](img/15QuickStart.png)

The overall process for adding an extension is as follows:

![](img/16QuickStart.gif)

<font style="color:rgb(13, 13, 13);">Once you've completed these steps, the extension will be successfully added.</font>



### <font style="color:rgb(13, 13, 13);">Start Coding</font>
<font style="color:rgb(13, 13, 13);">Now let's write a sample program on the programming platform.</font>

![](img/17QuickStart.png)

<font style="color:rgb(13, 13, 13);">This program will allow the fan and the red LED to turn on when the button is pressed, and turn off when the button is released.</font>



<font style="color:rgb(13, 13, 13);">The coding process is as follows:</font>

![](img/18QuickStart.gif)



## <font style="color:rgb(26, 26, 26);">Program Download</font>
Now you can connect the hub to your computer and download the program

**Step 1**<font style="color:rgb(13, 13, 13);">: Use a microUSB cable to connect the hub to your computer.</font>

![](img/19QuickStart.png)

**Step 2**<font style="color:rgb(13, 13, 13);">: Connect the device on the coding platform and download the program</font>

![](img/20QuickStart.gif)



<font style="color:rgb(13, 13, 13);">Notes:</font>

<font style="color:rgb(13, 13, 13);">Sometimes, due to an unstable USB connection, the download may fail. As shown below, the left side shows a successful download, while the right side shows a failed download. If the download fails, the program will be saved as a </font>`**<font style="color:rgb(13, 13, 13);">.hex</font>**`<font style="color:rgb(13, 13, 13);"> file on your computer. In case of failure, please reconnect the USB cable between the computer and the hub, and repeat Step 2.</font>

| ![](img/21QuickStart.png) | ![](img/22QuickStart.png) |
| :---: | :---: |
| **Successful Download**<font style="color:rgb(13, 13, 13);">: When the message "ownloaded" appears.</font> | **Failed Download**<font style="color:rgb(13, 13, 13);">: When the message "ownload Complete" appears, and the file is saved to your computer via the browser.</font> |


## <font style="color:rgb(13, 13, 13);">Run the Program</font>
![](img/23QuickStart.gif)

