# Make a Digital Timer!
 
## Overview
For this assignment, you are going to 

A) [Solder your LCD panel](#part-a-solder-your-lcd-panel)

B) [Write text to an LCD Panel](#part-b-writing-to-the-lcd) 

c) [Using a time-based digital sensor!](#part-c-using-a-time-based-digital-sensor)

D) [Make your Arduino sing!](#part-d-make-your-arduino-sing)

E) [Make your own timer](#part-e-make-your-own-timer) 
 
## In The Report
Include your responses to the bold questions on your own fork of [this lab report template](https://github.com/FAR-Lab/IDD-Fa18-Lab2). Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as README.md pages on your GitHub, and post a link to that on your main class hub page.

## Part A. Solder your LCD panel

**Take a picture of your soldered panel and add it here!**

![pic soldered panel](https://lh3.googleusercontent.com/5g3rR4Ii7BMHciiCa4smXQv8am9hlKQueFNfmu4JaNQLuA_MUbMunEsfcZFbM9ASgXGN2VLAlnVPKBhG-hb7w7BGU-a3udicVWAOZV_8V1rmM9AUGzvouUsA0G9oz2LB48ZqQ2P2cTM)

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?**

**b. What voltage level do you need to power the display backlight?**
   
**c. What was one mistake you made when wiring up the display? How did you fix it?**

**d. What line of code do you need to change to make it flash your name instead of "Hello World"?**

In the following sample code, I should change `lcd.print("hello, world!");` to `lcd.print("Lalo Gonzalez!");`

```
void setup() {
  // set up the LCD's number of columns and rows:
  lcd.begin(16, 2);
  // Print a message to the LCD.
  lcd.print("hello, world!");
}
```
**e. Include a copy of your Lowly Multimeter code in your lab write-up.**


## Part C. Using a time-based digital sensor

**Upload a video of your working rotary encoder here.**

[video](https://drive.google.com/file/d/1BZO-Ca3SzDQkHz8SQDSJJB7R71zjDyRm/view?usp=sharing)


## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**

By changing the note durations.
 
**b. What song is playing?**

Star Wars Song.

## Part E. Make your own timer

**a. Make a short video showing how your timer works, and what happens when time is up!**

[video](https://drive.google.com/file/d/1mjCmb_7g43O4OJAVd45jEFi8TSpaNc10/view?usp=sharingt)

**b. Post a link to the completed lab report your class hub GitHub repo.**