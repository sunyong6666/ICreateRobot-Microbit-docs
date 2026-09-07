# joystick
The joystick module is an I2C device and must be connected to the I2C port of the micro. Use the API to read data from the joystick module.



##  Required Libraries
`color.py`、`DC_motor.py`、`iic_base.py`、`joystick.py`



## Class   joystick_sensor
The `joystick_sensor` object is the basic object used to control the joystick module.



### Constructor
```python
class joystick_sensor(port=0, addr:int=0x61):
```

Create a joystick object from the files in `joystick`.



**Parameters**

+ **port**: Used to select the port. This parameter has no practical significance in micro and does not need to be configured. It is retained for compatibility.
+ **addr**: Sets the device address.



### Functions
#### get_x
+ get_x（）

 Get the X-Axis Value  



**Return Value**

 X-Axis Output Range:   -100 ~ 100



**Usage Examples：**

```python
from microbit import *

import joystick # Import the Joystick Module Library

joy = joystick.joystick_sensor() # Create the Joystick Module Handle

while True:
    print(joy.get_x()) # Output the X-Axis Value
    sleep(200)

```

****

#### get_y
+ get_y()

 Get the Y-Axis Value  



**Return Value**

Y -Axis Output Range:   -100 ~ 100



**Usage Examples：**

```python
from microbit import *

import joystick # Import the Joystick Module Library

joy = joystick.joystick_sensor() # Create the Joystick Module Handle

while True:
    print(joy.get_y()) # Output the Y-Axis Value
    sleep(200)

```

****



#### is_up
+ is_up()

 Get Whether the Joystick Is Tilted Upward  



**Return Value**

Returns `True` if the joystick is tilted upward; otherwise, returns `False`.



**Usage Examples：**

```python
from microbit import *

import joystick # Import the Joystick Module Library

joy = joystick.joystick_sensor() # Create the Joystick Module Handle

while True:
    if joy.is_up(): # Determine Whether the Joystick Is Tilted Upward
        print("up")
    else:
        print("no up")
    sleep(200)

```



#### is_down
+ is_down()

Get Whether the Joystick Is Tilted  Downward  



**Return Value**

Returns `True` if the joystick is tilted  downward  ; otherwise, returns `False`.



**Usage Examples：**

```python
from microbit import *

import joystick # Import the Joystick Module Library

joy = joystick.joystick_sensor() # Create the Joystick Module Handle

while True:
    if joy.is_down(): # Determine Whether the Joystick Is Tilted Downward
        print("down")
    else:
        print("no down")
    sleep(200)

```





#### is_left
+ is_left()

 Get Whether the Joystick Is Tilted Left  



**Return Value**

Returns `True` if the joystick is tilted left; otherwise, returns `False`.





**Usage Examples：**

```python
from microbit import *

import joystick # Import the Joystick Module Library

joy = joystick.joystick_sensor() # Create the Joystick Module Handle

while True:
    if joy.is_left(): # Determine Whether the Joystick Is Tilted left
        print("left")
    else:
        print("no left")
    sleep(200)

```



#### is_right
+ is_right()

 Get Whether the Joystick Is  Tilted Right  



**Usage Examples：**

```python
from microbit import *

import joystick # Import the Joystick Module Library

joy = joystick.joystick_sensor() # Create the Joystick Module Handle

while True:
    if joy.is_right(): # Determine Whether the Joystick Is Tilted right
        print("right")
    else:
        print("no right")
    sleep(200)
```



