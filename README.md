# piSenseHatDigitalClock

To run:

python piSenseClock.py 

SOME THINGS YOU  CAN CHANGE
If you want to mess around with your Sense HAT clock, I recommend looking over the code and tinkering with it.  It’s a great way to learn about Python and a great way to relax while experimenting at the same time.

CHANGE THE PI CLOCK’S COLORS
The colors are controlled by the following section of code.

hour_color = [0,0,255] -> Blue
minute_color = [248,226,55] -> Yellow
empty = [0,0,0] -> Black
#These are simply RGB values and you can made them anything you want.  RGB values come in strings of three.  The first number represents Red, the second number represents Green, and the third number represents Blue.  These colors are mixed together in different intensities to create the desired color.  Values range from 0 to 255.

#Some RGB examples:

255,0,0 would be bright red
100,100,100 would be a medium shade of grey
