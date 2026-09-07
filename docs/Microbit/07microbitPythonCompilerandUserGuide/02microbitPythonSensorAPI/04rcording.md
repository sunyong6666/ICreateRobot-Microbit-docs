# rcording
The audio recording module can play built-in audio files. It can also record audio through the button and play the recorded audio. The recording module is an I2C device and must be connected to the I2C port of the micro.



##  Required Libraries  
`color.py`、`DC_motor.py`、`iic_base.py`、`rcording.py`





## Class recording
The `recording` object is the basic object used to control the recording module.



###  Parameter Macros  
```python
GUNSHOT        
LASER          
MOTORCYCLE     
WARBEGIN       
COUNTDOWN      
PLAYRECORDING  
```

 Used to specify the type of audio to be played.  



###  Constructor  
```python
class recording(port=0, addr=0x18):
```

Create a light ring object from the files in `light_ring`.



** Parameters  **

+ **port **: Used to select the port. This parameter has no practical significance in micro and does not need to be configured. It is retained for compatibility.
+ **addr **: Sets the device address.



###  Functions  
#### voice
+ voice(index)

 Play Audio from the Recording Module  



**Parameters **

+ index     Audio Type  
    - GUNSHOT
    - LASER
    - MOTORCYCLE
    - WARBEGIN
    - COUNTDOWN
    - PLAYRECORDING





** Usage Examples  ：**

```python
from microbit import *

import recording # Import the Recording Module Library

rec = recording.recording() # Create the Recording Module Handle

rec.voice(recording.WARBEGIN) # Play the “War Start” Audio
while True:
    pass
    
```





