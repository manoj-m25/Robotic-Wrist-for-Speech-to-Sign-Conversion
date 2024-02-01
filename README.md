# Robotic-Wrist-for-Speech-to-Sign-Conversion
We have developed a robotic wrist that can convert speech into sign language and show  gestures with text being an intermediate stage and for this, we have used a speech recognition  model and Raspberry Pi 

In India, these days we can see a lot of people who cannot speak and hear though they want to hear what people talk about and want to express their thoughts. In the modern world, we have so many technologies, like hearing aids, and amplified phones, that can help these kinds of people but usually, they will be of prohibitive cost which cannot be afforded by middle- and lower-class people in India.
The primary causes of deafness in adults are Neonatal Septicemia, prematurity, low birth weight, consanguinity, and birth asphyxia in infants, among others. The primary causes of dumbness in humans are physical problems with the lips, palate, or other parts of the mouth that may be malformed, or Ral-motor dysfunction, which is a problem with the development of the particular region of the brain that controls speech and communication.
As a result, we created this project, which is both low-cost and capable of demonstrating sign language, to address these issues.

Servo Motor Setup

•	We have connected the servo motor terminals to the Raspberry Pi GPIO pins 18, 11,13, 15, and 16.
•	The DC positive power supply is linked to the VCC terminal of each servo motor
•	The Raspberry Pi's GPIO pins are linked to the signal terminal of each servo motor.
•	The negative DC power supply is linked to the ground terminal of each servo motor
•	Using Breadboard, both positive and negative DC power supply is short-circuited and then connected with the VCC and the ground terminal of each servo motor. 

LCD Display and I2C Setup

•	Connected all the terminals of the LCD to the I2C module using a Breadboard.
•	There are 4 terminals in the I2C namely GND, VCC, SDA, and SCL.
•	The Raspberry Pi's GPIO pins are connected to these 4 terminals.
•	The GND terminal is connected to GPIO pin 4.
•	The VCC is connected to GPIO pin 6.
•	SDA (data terminal) is connected to GPIO pin 3.
•	SCL (clock terminal) is connected to GPIO pin 5.

DC Power Supply Setup

•	We have employed the Switching approach, in which the power supply is more effective, lighter, and smaller.
•	In our project, we connected the negative terminal of the DC power supply and the positive cable to the positive terminal of the DC power supply. Then, we used a breadboard to short-circuit the power supply.
•	In our project, we have set the Current to 2.25A and Voltage to 7.2

Microphone Setup 

•	In this project, we are using a Microphone for taking the input which we have connected directly to the laptop.
•	The Microphone that we are using in this project has a signal of 74dB SPL and output impedance of 1000ohm or less and a frequency range of 65Hz –18KHz.


