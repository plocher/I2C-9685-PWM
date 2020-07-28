# I2C-LEDStripDriver
## License: CERN Open Hardware Licence v1.2


I2C 16 channel PWM Driver based on a PCA9685 

The PCA9685 is an I2C-bus controlled 16-channel LED controller optimized for Red/Green/Blue/Amber (RGBA) color backlighting applications.  It can also be used to control Servos.
Each output has its own 12-bit resolution (4096 steps) fixed frequency individual PWM controller

This design, when used in conjunction with the IO4-LED_STRIP driver board, drives RGB + "white" LED strips - I use one set for backdrop lighting (dawn and dusk sunsets...) and the other for overhead (sunlight) valence illumination.


