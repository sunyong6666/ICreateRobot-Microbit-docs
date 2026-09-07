# servo_motor
The servo motor has an integrated control chip that regulates its rotational speed and operating state, enabling precise control of motor speed and rotational position. The servo motor is an I2C device and must be connected to the I2C port of the micro.



## Required Libraries
`color.py`、`DC_motor.py`、`iic_base.py`、`server_motor.py`



## Parameter Macros
```python
GENERAL       # Generic Address
LIGHT_RED     
LIGHT_GREEN   
LIGHT_BLUE    
LIGHT_YELLOW  
```

 These macros are used to select the motor address when creating an object. The selected address must match the color of the indicator LED on the motor.  



## Class   motor
The `motor` object is the basic object used to control a single motor.

### Constructor
```python
class servo_motor.motor(port=0, addr=0x50)
```

Create a single motor object from the files in `motor`.



**Parameters**

+ **port**: Used to select the port. This parameter has no practical significance in micro and does not need to be configured. It is retained for compatibility.
+ **addr**: Sets the device address.



### Functions
#### run
+ run(velocity)

 Set the Motor Operating Speed  



**Parameters**

+ velocity speed

> range -100 ~ 100
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create the Servo Motor Handle. Here, it is assumed that the indicator LED on the motor is blue.
sm = server_motor.motor(addr=server_motor.LIGHT_BLUE)

while True:
    sm.run(50) # Set the Motor Speed
    sleep(200)
```





#### run_for_time
+ run_for_time(velocity, duration, isBlock=True)

Specify the Motor Speed and Operating Duration



**Parameters**

+ velocity     Rotation Speed  

> Range -100 ~ 100
>

+ duration    Duration  

>  Unit: seconds; range:   0 - 6553
>

+ isBlock       Blocking  

> The default value is `True`, which means the program will continue execution only after the current action is completed.
>
> When set to `False`, the operation is non-blocking, and the program continues execution without waiting for the current action to complete.
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create the Servo Motor Handle. Here, it is assumed that the indicator LED on the motor is blue.
sm = servo_motor.motor(addr=servo_motor.LIGHT_BLUE)

while True:
    # Rotate at a speed of 50 for 2 seconds
    sm.run_for_time(50, 2)
    sleep(1000)
    # Rotate at a speed of -50 for 2 seconds
    sm.run_for_time(-50, 2)
    sleep(1000)
```





#### run_to_absolute_position
+ run_to_absolute_position(velocity, position, isBlock=True)

Specify the Motor Speed and Operating Duration



**Parameters**

+ velocity Rotation Speed

> Range  0 ~ 100
>

+ position  Absolute Position  

>  Unit: degrees; range:   -32768 ~ 32767
>

+ isBlock Blocking

> The default value is `True`, which means the program will continue execution only after the current action is completed.
>
> When set to `False`, the operation is non-blocking, and the program continues execution without waiting for the current action to complete.
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create the Servo Motor Handle. Here, it is assumed that the indicator LED on the motor is blue.
sm = servo_motor.motor(addr=servo_motor.LIGHT_BLUE)

while True:
    # Rotate to 90 degrees at a speed of 50.
    sm.run_to_absolute_position(50, 90)
    sleep(1000)
    # Rotate to -90 degrees at a speed of -50.
    sm.run_to_absolute_position(50, -90)
    sleep(1000)
```





#### run_to_relative_position
+ run_to_relative_position(velocity, position, isBlock=True)

Rotate to a Relative Position at the Specified Speed



**Parameters**

+ velocity Rotation Speed

> range 0 ~ 100
>

+ position Relative Position

>  Unit: degrees; range:   -32768 ~ 32767
>

+ isBlock  Blocking

> The default value is `True`, which means the program will continue execution only after the current action is completed.
>
> When set to `False`, the operation is non-blocking, and the program continues execution without waiting for the current action to complete.
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create the Servo Motor Handle. Here, it is assumed that the indicator LED on the motor is blue.
sm = servo_motor.motor(addr=servo_motor.LIGHT_BLUE)

while True:
    # Rotate 90 degrees relative to the current position at a speed of 50.
    sm.run_to_relative_position(50, 90)
    sleep(1000)
    # Rotate -90 degrees relative to the current position at a speed of 50.
    sm.run_to_relative_position(50, -90)
    sleep(1000)
```





#### get_absolute_position
+ get_absolute_position()

 Get the Motor's Absolute Position  



**return value  **

 Motor Absolute Position， Range   -32768 ~ 32767



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create the Servo Motor Handle. Here, it is assumed that the indicator LED on the motor is blue.
sm = servo_motor.motor(addr=servo_motor.LIGHT_BLUE)

while True:
    # Set the Motor Speed
    sm.run(50)
    # Get the Motor's Absolute Position
    print(sm.get_absolute_position())
    sleep(200)
```



## Class   motor_pair
 The `motor_pair` object is the basic object used to control two motors.  



### Constructor
```python
class servo_motor.motor_pair(port1=0, port2=0, addr1:int=0xff, addr2:int=0xff)
```

Create a dual-motor object from the files in `motor`.



**Parameters**

+ port1 
+ port2

> `**port1**`** and **`**port2**`: Used to select the ports. These parameters have no practical significance in micro and do not need to be configured. They are retained for compatibility.
>

+ addr1
+ addr2

> `**addr1**`** and **`**addr2**`: Used to set the addresses of the two motors. The default parameter value `0xFF` cannot be used; valid addresses must be specified.
>



### Functions
#### move
+ move(velocity1, velocity2)

 Set the speeds of the two motors independently.  



**Parameters**

+ velocity1   Left Motor Speed  
+ velocity2   Right Motor Speed  

> Motor Speed Range   -100 ~ 100
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create the Servo Motor Handle. Here, it is assumed that the indicator LED on the left motor is blue 
#  the indicator LED on the right motor is red.
smp = servo_motor.motor_pair(addr1=servo_motor.LIGHT_BLUE, addr2=servo_motor.LIGHT_RED)

while True:
    smp.move(50, -50) # Set the Speeds of the Left and Right Motors
    sleep(200)
```





#### move_for_time
+ move_for_time(velocity1, velocity2, duration)

Specify the dual Motors Speed and Operating Duration



**Parameters**

+ velocity1  Left Motor Speed  

> range  -100 ~ 100
>

+ velocity2   Right Motor Speed  

> range -100 ~ 100
>

+ duration   Duration  

>  Unit: seconds; range:   0 - 6553
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create a servo motor handle, assuming that the indicator LED on the left motor is blue
# the indicator LED on the right motor is red.
smp = servo_motor.motor_pair(addr1=servo_motor.LIGHT_BLUE, addr2=servo_motor.LIGHT_RED)

while True:
    # Rotate the left motor at a speed of 50 and the right motor at a speed of -50 for 2 seconds.
    smp.move_for_time(50, -50, 2)
    sleep(1000)
    # Rotate the left motor at a speed of -50 and the right motor at a speed of 50 for 2 seconds.
    smp.move_for_time(-50, 50, 2)
    sleep(1000)
```





#### move_to_relative_position
+ move_to_relative_position(velocity1, velocity2, position)

Rotate to a Relative Position at the Specified Speed



**Parameters**

+ velocity1          Left Motor Rotation Speed

>  Motor Speed  Range    -100 ~ 100
>

+ velocity2          Right Motor Rotation Speed

> Motor Speed  Range -100 ~ 100
>

+ position    Duration

>  Unit: seconds; range:   0 - 6553
>



**Usage Examples：**

```python
from microbit import *

import servo_motor # Import the Servo Motor Library

# Create a servo motor handle, assuming that the indicator LED on the left motor is blue
# the indicator LED on the right motor is red.，
smp = servo_motor.motor_pair(addr1=servo_motor.LIGHT_BLUE, addr2=servo_motor.LIGHT_RED)

while True:
    # Rotate the left motor at a speed of 50 and the right motor at a speed of 50 to a position 90° relative to their respective current positions.
    smp.move_to_relative_position(50, 50, 90)
    sleep(1000)
    # Rotate the left motor at a speed of 50 and the right motor at a speed of 50 to a position -90° relative to their respective current positions.
    smp.move_to_relative_position(50, 50, -90)
    sleep(1000)
```













