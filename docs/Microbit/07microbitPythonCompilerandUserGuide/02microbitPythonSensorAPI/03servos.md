# servos
 A servo is a motor system that can continuously adjust and maintain the angle of its output shaft within a specific range under program control.  



## Notes
+ The servo interface consists of three wires. It must be connected to the interface marked with a silk-screen label such as `S1` on the micro. Pay attention to the connection direction. If the servo is connected in the wrong direction, it will not function properly.



## Required Libraries
`color.py`、`DC_motor.py`、`iic_base.py`、`servos.py`

 

## Parameter Macros
```python
S1 
S2
S3
S4
```

 These macros are used for port selection when creating an object.  





## Class servos
The `servos` object is the basic object used to control a single servo motor.



### Constructor
```python
class servos.servos(port)
```

Create a single motor object from the files in `DC_motor`.



**Parameters**

+ port           Motor Port  
    - S1
    - S2
    - S3
    - S4

> The selected port corresponds to the port connected to the micro. Connect the motor to the micro port with the matching silk-screen label.
>



### Functions
#### write_angle
+ write_angle(angle:int)

 Set the Servo Angle  



**Parameters**

+ angle 

>  Range   0 ~ 180
>



**Usage Examples：**

```python
from microbit import *

import servos # Import the Servo Motor Library

# Create a servo motor handle and specify the port as S1
ser = servos.servos(servos.S1)

while True:
    # Set the Servo Angle
    ser.write_angle(0)
    sleep(1000)
    ser.write_angle(90)
    sleep(1000)

```



