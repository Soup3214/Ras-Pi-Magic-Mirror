# Arduino Binary Clock
Nowdays, reading the time is boring. All one needs to do is to take a glance at their phone or their computer, or even a glance at their desk and all the information they need, will be right there for them. This clock challenges people and changes this by using binary codes to show the time.  

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aaron Fang | Paly | Undecided | Upcoming Sophomore 

![Headstone Image](https://cdn.discordapp.com/attachments/799773888032014406/857099616511328276/IMG_0419.jpg)(second to last green is really dim)
  
# First Milestone: Learning to read time with Arduino 
My first milestone I made for myself in the process of making the clock was to learn how to track time passing using an Arduino, I had to do this because reading the time is the most important feature of a clock. In order to do this, I started off with the millis(); function to keep track of the time since the Arduino started. Then with this, I could add certain timed events to happen. In this case, I wrote "time to dance".

[![First Milestone](https://cdn.discordapp.com/attachments/799773888032014406/858075178101768232/Screen_Shot_2021-06-25_at_1.01.29_PM.png)](https://youtu.be/JirGGPNNe5g&feature=emb_logo "First Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second Milestone was for me to have finished the physical build. I didn't want to worry about the code in that time. So I decided to get the physical build done first. This was done by first wiring up 13 LEDS to a breadboard, therefore making a small prototype for the physical build. Then I decided I wanted to solder the wires into a perf board to make the clock more permanent than if I were to use a breadboard. After soldering the wires into a breadboard, the next logical step was for me to put it into a container which would allow me to show the time how I wanted. 

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/vvg8xu6B3hI){:target="_blank" rel="noopener"}
# Last Milestone
The last milestone I set for myself was for me to complete the build, physical and the code. Since I already had the physical build done, I needed to get the code done. Originally, I planned on using a few buttons to manually need to change the time. Sort of like a regular clock. Then I shifted my plan to use a RTC chip to be able to track the time. With the RTC in, All I needed to do was convert the RTC time into a way showable by the LED’s in the front. And once that was done. The clock was complete. You could tell what time it was just from the LEDs. 



[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}

If you want the code, go check the Arduino LED Binary Clock repository I have made here: https://github.com/Soup3214/Binary-LED-arduino-Clock.git
