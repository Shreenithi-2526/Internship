# WEEK 7

## PCB Caliberation

We had to calibrate 3 PCBs that are used in a small CNC milling machine. We used the Arduino Due board to make connections to the PCB in the following way: 

[Connections](IMG38.jpeg)

We uploaded a code from the Arduino IDE to the board to achieve a 50% duty cycle through PWM. However, upon uploading, we found that the board did not receive the required voltage as measured by the multimeter, indicating an error with the Arduino Due.

Therefore, we changed the board to an ESP32 Developer kit and uploaded the same code again using the same connections. This time it worked, and we reached the desired voltage using the potentiometer.


[Calibration](IMG39.jpeg)

Next, we connected this calibrated PCB to the small CNC machine. Since it is used for spindle control, we checked if the spindle is functioning properly and responding to commands using UGS.

We repeated the same process for the other two PCBs. However, one of them was problematic because it was soldered incorrectly and could not be calibrated.

## Drilling & Tapping

For a workshop set to take place at the end of May, a small CNC milling machine is to be prepared. Our goal was to drill and tap holes on aluminum profiles, align and screw the pieces for the assembly of this machine. We were first trained by our colleague and practiced drilling on test pieces before proceeding to the actual task. Since some holes drilled were blind, tapping them manually was a better option. 

[Drilled Profile](IMG40.jpeg)

 [Profiles for drilling and tapping](IMG41.jpeg)

Various profiles for this machine were tapped and drilled and it continued till the next week.

## Soldering

A Teensy microcontroller was soldered to male headers.



