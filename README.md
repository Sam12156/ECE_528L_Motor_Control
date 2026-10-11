# Overview
This lab introduces Pulse Width Modulation (PWM) and interrupts on the TI MSP432
LaunchPad mounted on the TI-RSLK MAX chassis. Timer_A is configured to generate PWM signals that drive two
 HS-485HB servos and the robot's two DC motors (through the TI DRV8838 drivers). The front bumper
 switches are configured to send interrupts on Port 4, and a collision-handling routine moves 
 the robot through a predefined pattern whenever an obstacle is hit. PWM outputs and switch bouncing
 are verified on an oscilloscope.
### Objectives


![Servo 0 degrees](Screenshots/ece528L_lab1_servo_0_degrees_pulse_width_group_Sammy_Hamed.JPG)
Servo 0 degee position
![Servo 180 degrees](Screenshots/ece528L_lab1_servo_180_degrees_pulse_width_group_Sammy_Hamed.JPG)
Servo 180 degree position
![Bumper switch bounce](Screenshots/ece528L_lab1_bumper_scope_shot_group_Sammy_Hamed.JPG)	
Bumper switch bounce and led
# Components Used:

* TI MSP432 LaunchPad
* Pololu Gearmotor with Encoder - [Product Link](https://www.pololu.com/product/3675)
* Left Bumper Switches for TI-RSLK MAX - [Product Link](https://www.pololu.com/product/3673)
* Right Bumper Switches for TI-RSLK MAX - [Product Link](https://www.pololu.com/product/3674)
* HS-485HB Servo-Stock Rotation - [Product Link](https://www.servocity.com/hs-485hb-servo/)

# Known Issues or Limitations:

