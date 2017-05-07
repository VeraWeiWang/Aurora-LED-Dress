# Aurora Dress

### Introduction

Aurora Dress is a fantastical dress on which 44 LEDs blink in different colors and patterns according to the different movements of the wearer. It is a combination of art and science, or design and technology, to stimulate inspirations, excite imaginations, and create dreamy interactive experiences for users.

An absolute orientation sensor attached to the dress is used to detect Euler angles, accelerations, angular velocities, and angular accelerations of the wearer in different directions. Then an Arduino Uno processes these data and controls the blinking of 44 RGB Smart neoPixel LEDs to create different patterns: rainbow-like aurora for staying static, theatre chasing for jumping, wiping for spinning, etc.

### Technology

- An BNO055 absolute orientation sensor is used to detect the movement of the wearer.
- 44 Adafruit Smart neoPixels are solded and sewed onto a dress. 
- Programming in Arduino to define colors and glittering pattern of LEDs according to signals of movement.
- Time-lapse photography

### Process

Sketch:

![led dress - sketch](https://cloud.githubusercontent.com/assets/23609156/23991460/b59e5536-09f6-11e7-823c-9412d0168fff.jpg)

Schemetic of BNO055 Absolute Orientation Sensor:

- Connect Vin to the power supply, 3-5V is fine. Use the same voltage that the microcontroller logic is based off of. For most Arduinos, that is 5V
- Connect GND to common power/data ground
- Connect the SCL pin to the I2C clock SCL pin on your Arduino. On an UNO & '328 based Arduino, this is also known as A5, on a Mega it is also known as digital 21 and on a Leonardo/Micro, digital 3
- Connect the SDA pin to the I2C data SDA pin on your Arduino. On an UNO & '328 based Arduino, this is also known as A4, on a Mega it is also known as digital 20 andon a Leonardo/Micro, digital 2

PCB:

Connection of Adafruit NeoPixels:





### Continuing



