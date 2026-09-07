# oled
OLED (Organic Light-Emitting Diode) is a self-emissive display technology that displays different patterns or text by controlling the on/off state of individual pixels on the screen. The OLED module is an I2C device and must be connected to the I2C port of the micro.



##  Required Libraries  
`color.py`、`DC_motor.py`、`iic_base.py`、`oled.py`



## Class  oled
The `oled` object is the basic object used to control the OLED module.



### Constructor
```python
class oled.oled(port=0, addr=0x3c)
```

Create an OLED object from the files in `oled`.



**Parameters**

+ **port**: Used to select the port. This parameter has no practical significance in micro and does not need to be configured. It is retained for compatibility.
+ **addr**: Sets the device address.



### Functions
#### set_text
+ set_text(x, y, text, color=1)

 Set the Display Text at the Specified Position  



**Parameters**

+ x      
+ y      
+ text  
+ color 

> The default value is `1`, which displays white text on a black background.
>
> Set the value to `0` to display black text on a white background.
>



**使用案例：**

```python
from microbit import *

import oled # Import the OLED Library

oled_display = oled.oled() # Create the OLED Handle

count=0 #Define the count Variable

while True:
    oled_display.set_text(0, 0, "hello", 0) # Display the string hello on the first line using black text on a white background. hello String
    # Display the count value on the second line using white text on a black background.
    oled_display.set_text(0, 1, "count: %d  "%(count))
    count += 1 # Increment the count Variable
    if count>99: # When count reaches 100, reset it to 0.
        count=0
    sleep(400)
```





#### clear_screen
+ clear_screen()

**Clear the Screen**: Clears the screen and sets all pixels to black.



**使用案例：**

```python
from microbit import *

import oled # Import the OLED Library

oled_display = oled.oled() # Create the OLED Handle

count=0 #Define the count Variable
 # Display the string hello on the first line using black text on a white background. hello String
oled_display.set_text(0, 0, "hello", 0)
sleep(2000)
# Clear the Screen
oled_display.clear_screen()
while True:
    pass
```













