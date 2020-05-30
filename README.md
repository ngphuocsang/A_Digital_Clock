# A_Digital_Clock
This is a digital clock with 2 buttons and 3 functions: displaying time, adjusting hour, minute or second and stopwatch. The counting time
is thanks to the timer of the MCU which was set to 2ms. 

The two buttons:
  - The mode button: It's used to exchange modes of the digital clock: adjusting time and running the stopwatch.
  - The modifying button: press it to increase the value in adjusting hour, minute and second modes. Besides, when the digital 
  clock in stopwatch mode, this button function is to transit the states: RUN/STOP - run/stop the stopwatch, RESET - set all 
  values of the stopwatch to zero.
 
The three functions: In each mode, the LCD displays the mode name and time.
  - Displaying time: Show time on the 16x2 LCD.
  - Modifying time: Set time to what you want. If the hour number is being adjusted, it will blink. It's the same for minute and 
  second one.
  - Stopwatch: The accuracy of this clock is one percent of second.
