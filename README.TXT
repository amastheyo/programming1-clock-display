Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

Question 21:
It starts at "00:00" because the default constructor sets both hours and minutes to 0. It does not read the current system time. It’s instead initializing to a default starting point — midnight (00:00).

Question 23:
We can use the method "setTime(1, 0)"

Question 24:
I would write "NumberDisplay digit = new NumberDisplay(10);"

Question 25:
Rectangle window = new Rectangle(100, 50);

Question 26:
The second constructor allows you to create a ClockDisplay object and initialize it to a specific time, instead of always starting at 00:00.

Question 27:
Both constructors initialize the clock, but the second one gives you control over the starting time.
