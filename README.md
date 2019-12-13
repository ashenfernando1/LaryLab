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
### To-Do
- Put all three sensors on one output, just the code for now
- Use pyserial to get timestamps for when input is received from USB and eventually collect data into csv
