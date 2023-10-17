## SmartCar
Combine the Freenove 4WD Smart Car for Raspberry Pi with various AI blocks.  

### Project 1: Room 3D model
The first project is implement a room exploration algorithm coupled with obstacle avoidance to avoid crashing the car. Once the room explored the output should be a video of the room, this will then be fed to Neuralangelo (https://github.com/NVlabs/neuralangelo) to build a 3D surface model of my room.

- [x] Freenove 4WD Smart Car built
- [x] Raspberry Pi 3 configuration completed
- [x] Car sensors tested (image, obstacle distance, sound and led)
- [ ] Obstacle avoidance algorithm
- [ ] Room exploration algorithm
- [ ] Use Neuralangelo to build a 3D surface model of my room with the video taken from the car

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
