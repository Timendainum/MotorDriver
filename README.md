MotorDriver
===========

Arduino Motor Driver for Seeed Studio Motor Driver. (rewired)

I have forked this from the Seeed Studio code found here:
http://www.seeedstudio.com/wiki/Motor_Shield_V2.0
http://www.seeedstudio.com/wiki/File:MotorDriver20121210.zip

I have rewired this to not use pin 10 and 11, such that controlling a servo will not disrupt operation of the motor shield. This is configured to use pins 5 and 6. This can be changed by modifying the setting in MotorDriver.h
