attiny85 Sleep 
=================

I have been attempting to make alot of LED/Blinkie Toys/Reading Lights for my kids who never turn the power switch off on stuff, so I wanted to make a baseline low-power sketch to start from so I am not constantly replacing batteries.

Assuming my measurements/calculations are correct, in sleep mode with an interrupt enabled for a single button a toy built on this code should consume .5 mA which would last for 150 days on 1800 mAh Eneloop AA batteries. Obviously, less depending on what it does when it's awake.

I would also like to eventually turn on a timer to enter sleep mode for projects that don't have a finite awake routine.
