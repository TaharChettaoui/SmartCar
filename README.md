### Introduction
The goal of this repo is to combine the Freenove 4WD Smart Car for Raspberry Pi with various AI blocks.

### Current State
- [x] Freenove 4WD Smart Car built
- [x] Raspberry Pi 3 configuration completed
- [x] Car sensors tested (image, obstacle distance, sound and led)

### Useful commands for car control

|   | Command  |
|---|---|
| Sound test  | sudo python test.py Buzzer   |
| LED test | sudo python test.py Led |
| LED possibility | sudo python Led.py |
| Motor test  | sudo python test.py Motor  |
| Voltage check | sudo python test.py ADC  |
| Obstacle distance | sudo python test.py Ultrasonic  |
| Line tracking | sudo python test.py Infrared  |
| Take Image | raspistill -o image.jpg  |
| Light tracing Car | sudo python Light.py  |
| Ultrasonic Obstacle Avoidance Car | sudo python Ultrasonic.py  |
