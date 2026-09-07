#  light_ring
The light ring module contains eight WS2812 LEDs, which can display different colors and brightness levels. When using the light ring module, connect it to the micro port marked with a label such as `P13P0`.



## Notes
 When the brightness is not configured, the light ring operates at a relatively low brightness. When the brightness is increased using the brightness-setting function described below, the light ring can become very bright. Avoid looking directly at the light ring to prevent eye discomfort or potential eye damage.  



## Required Libraries
`color.py`、`DC_motor.py`、`iic_base.py`、`light_ring.py`



## Class   light_ring
The `light_ring` object is the basic object used to control the light ring module.



### Parameter Macros
```python
P13P0 
P14P1 
P15P2 

P7P8   
P9P12  
P10P16
```

 These macros are used for port selection when creating an object.  



### Constructor
```python
class light_ring(port):
```

Create a light ring object from the files in `light_ring`.



** Parameters**

+ port       Port Selection  
    - P13P0
    - P14P1
    - P15P2
    - P7P8
    - P9P12
    - P10P16

> The selected port corresponds to the port connected to the micro. Connect the device to the micro port with the matching silk-screen label.
>

### Functions
#### light
+ light(light)

 Set the Light Ring Brightness  .This function must be called before using the `color` function. Calling this function alone does not directly change the current brightness. The brightness is updated only when the `color` function is called.



** Parameters：**

+ light     Brightness  

>  Returns a value in the range of   0~255
>



#### color
+ color(color)

 Set and Display the Light Ring Color  



** Parameters**

+ color    Light Ring Color  

> + You can use the predefined colors in the `color` file.
> + You can also use a tuple, for example, `(255, 0, 0)`.
>



**Usage Examples：**

```python
from microbit import *

import color      # Import the Color Library
import light_ring # Import the Light Ring Library

lr = light_ring.light_ring(light_ring.P15P2) # Create a Light Ring Handle and Specify the Port as P15P2

lr.light(40) # Set the Brightness
while True:
    lr.color(color.BLUE) # Display a Color Defined in the color File
    sleep(1000)
    lr.color((255, 0, 0)) # Display a Color Using a Tuple
    sleep(1000)
```

****













