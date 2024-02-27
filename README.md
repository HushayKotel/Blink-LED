Arduino LED Blink Program

DESCRIPTION:
This Arduino program is designed to blink an LED connected through a USB port on
and off with a 100-millisecond delay for each state. The LED blinks rapidly at 
this rate, creating a noticeable blinking effect.

SET UP INSTRUCTIONS:
1. Connected the Arduino through a USB Port
2. Used the Arduino IDE to write instructions(code) that would cause the Arduino
   blink. 
3. In the setup() part of the code, we declare whether a device is connected to
   the Arduino Board output and input devices.  
4. The main program is written in the "loop" section and this will cause it to 
    implement repeatedly. 
5. The first line of code "int led1 = 7", where 7 represents the digital pin 7 
6. In the setup() we use the function pinMode(pin, mode) which depends on the 
   device whether input or output, in this case we used pinmode(7, OUTPUT) 
7. To switch on the LED, we use digitalWrite(led1, HIGH) and for the wait time,
   we will call a delay. 
8. To switch off the LED, we use digitalWrite(led1, LOW)
9. After this, select the right port option and board option after which the 
    code is uploaded. 

USAGE:
Once the program is uploaded to the Arduino board, the LED will start blinking 
rapidly. You can modify the delay value in the code to adjust the blinking speed.