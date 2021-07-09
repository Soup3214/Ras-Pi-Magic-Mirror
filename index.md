# Raspberry PI Magic Mirror
Nowdays, many people will wake up and look at their phone to catch up on everything that they need. Such as the time, weather, news, and many more. They also will go and possibly look at their mirror. This project combines both of these into one, allowing for easy accsess to all the info one needs in the morning. 
| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Aaron Fang | Paly | Undecided | Upcoming Sophomore 

![Headstone Image](https://cdn.discordapp.com/attachments/799773888032014406/857099616511328276/IMG_0419.jpg)
  
# First Milestone: Setting up the Raspberry PI, a VNC server, as well as adding the Magic Mirror software
Since this was the first time I have ever used a Raspberry PI, I decided that learning how to turn it on was a good starting point. If you know raspberry pi, then starting up for the first time is a simple process, just downloading the raspberry pi imager, stick in a SD card, and write it up. Since I had a moniter, it was a simple task of plugging in the newly written SD card, adding the power supply, a HDMI cable, a mouse and keyboard, and with that the Raspberry pi is set up. setting up a VNC server was a bit harder. A VNC server is a program that allows me to remotely accsess my raspberry pi, a bit like a vertual desktop. 

[![First Milestone](https://cdn.discordapp.com/attachments/799773888032014406/858075178101768232/Screen_Shot_2021-06-25_at_1.01.29_PM.png)](https://youtu.be/JirGGPNNe5g&feature=emb_logo "First Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second Milestone was for me to have finished the physical build. I didn't want to worry about the code in that time. So I decided to get the physical build done first. This was done by first wiring up 13 LEDS to a breadboard, therefore making a small prototype for the physical build. Then I decided I wanted to solder the wires into a perf board to make the clock more permanent than if I were to use a breadboard. After soldering the wires into a breadboard, the next logical step was for me to put it into a container which would allow me to show the time how I wanted. 

[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/vvg8xu6B3hI){:target="_blank" rel="noopener"}
# Last Milestone
The last milestone I set for myself was for me to complete the build, physical and the code. Since I already had the physical build done, I needed to get the code done. Originally, I planned on using a few buttons to manually need to change the time. Sort of like a regular clock. Then I shifted my plan to use a RTC chip to be able to track the time. With the RTC in, All I needed to do was convert the RTC time into a way showable by the LED’s in the front. And once that was done. The clock was complete. You could tell what time it was just from the LEDs. 



[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}

If you want the code, go check the Arduino LED Binary Clock repository I have made here: https://github.com/Soup3214/Binary-LED-arduino-Clock.git
