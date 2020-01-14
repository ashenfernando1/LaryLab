# LaryLab

## 11/12/2019

### Done
- Ran three different sensors on Platformio
    - Grove Baromterer BME 280
    - Grove Sunlight 
    - LightGestureColorProximity TMG39931
- Put all three sensors on one output, code and the physical setup
    - the three sensors were in 'parallel', which was simply twisting wires for SDA, SCL, GND, VIN together. 
        - Note: SDA=White=A4, SCL=Yellow=A5, GND=Black, VIN=Red=5V, typically
- When importing new libraries, check on platformio for pre-existing ones. If downloading, can have platformio unzip the whole library, and also specify a global path

### To-Do
- Use pyserial to get timestamps for when input is received from USB and eventually collect data into csv
- Read Lakitha's thesis proposal

## 13/12/2019 - Group Meeting

## 08/01/2020

### Notes
- Central Node (Lakith's project) has 6 different components (with another Lightning/audio sensor coming from John)
    - Ozone sensor
    - LORA
    - PC
    - Power
    - Light sensor
    - Air sensor
- Objective is to create 10 of these Central Nodes

### Done
 - Took down dimensions of the Ozone sensor's housing and the board on which the sensor is seated on 

### To-Do
- Draw up the dimensions on FreeCAD
- Read up on the 3D printing documentations and produce the boards 
- Follow up with Lakitha on setting up the circuit and completing the Ozone sensor (this step should have multiple sub-steps)
- Move on to the other sensors on the Central Node

## 13/01/2020

### Done 
- Finished up the 3D model, 20% printed board available at the end of the day
- Retrieved ozone sensor data into a csv file. Of course, complete code already written up on mints git. 

### To-Do
- Set up Ozone sensor box with Lakitha tomorrow 
- Review serial port reading code some more
