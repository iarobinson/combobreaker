## Overall

First off, I don't know anything about robotics. This is my first foray into this game. If you're just starting like me, I hope these notes provide a step-by-step process for learning this stuff for the first time.

# My process

1. Order all the parts from Sammy.pl/combobreaker
2. Arduino Software (arduino.cc)


## Ordering the Parts

This is all easy via Sammy's link (Sammy.pl/combobreaker) the parts look like this once they arrive and are parsed down to what is needed:

![alt tag](https://github.com/iarobinson/combobreaker/blob/master/ian_notes/image/01combobreaker_parts.jpg)

## Learning to Program Arduino

First off, I'd like to run a simple program to ensure I'm able to successfully write code to the micro-controller.

I found this tutorial useful for making the first move:
https://www.arduino.cc/en/tutorial/blink

This helped me overcome initial steps like setting the serial port and selecting the right device.

### Servo Swipe: Wiring and Program

My initial goal is to just get movement out of anything. The first thing I was able to do was get the S1213 Analog Servo to sweep back and forth.

[alt tag]https://github.com/iarobinson/combobreaker/blob/master/ian_notes/image/03servo_wiring.jpg

Process:
1. Plug your Arduino nano into the breadboard. It doesn't matter where specifically, but look to the image for guidance
2. Extend the wiring of the servo using male wires
3. Push the wires into the breadboard so that they align with the pin number on the Arduino (note: don't use the numbers on the breadboard. In my example, GND is on row 12 of the breadboard.) Here's the wiring guideline:
- Orange      = D9
- Black/Brown = GND
- Red         = 5V
4. Upload the source code from [https://www.arduino.cc/en/Tutorial/Sweep] to your Arduino (it can be found in Arduino code in this repository too.)
5. Now your servo should start wiping back and forth.

This is actually the story of my first robot. No matter how little that first step is, it's helpful.

##
