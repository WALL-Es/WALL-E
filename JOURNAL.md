# WALL-E

> **Contributors:**
> - [![@Nadoooor](https://img.shields.io/badge/@Nadoooor-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/Nadoooor)
> - [![@ZIZO932](https://img.shields.io/badge/@ZIZO932-d97706?style=flat-square&logo=github&logoColor=white)](https://github.com/ZIZO932)

---

## Day 1 [![@Nadoooor](https://img.shields.io/badge/@Nadoooor-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/Nadoooor)

- **Date:** 14/9/2026
- **Total hours spent:** 2.5 hours

### Entry:

AHM AHM, uhhhh, this is my first time to work with someone on the same projct wow. 

uhh, wellll, this is kinda cool tbh, we are learning how to use github together and how to use the branches and many other things.

Well, this journal will be color coded with the user name of the Entry's writter, so i hope it will be easy for you to review.

Anyways, let me quickly say what i did in these hours.

Well, I started a huddle with my friend Ziad and we worked together at the same time to think on how we will make this project, well we started searching for already made clones, and we found manyyyyy.

So he started searching on his part (which is 3D CAD), and i started searching about the circuit and the PCB.

Well, i started searching about the circuits and we found this [youtube vid](https://www.youtube.com/watch?v=r7WV-IAMnDo), and from it i found this [site](https://www.huyvector.org/robots-kinetic/full-3d-wall-e-ai).

And it had a really help full circuit and data,

![alt text](Images/Journal/1cir.png)

but i won't just copy it, tbh we need to learn more in this journey, so we will use with that all, a PI zero w, and ROS2 to build it all in simulation. So i added it to our [figjam](https://www.figma.com/board/f0VK2TiKBMFvHDcY7YVH4b/WALL-E?node-id=0-1&p=f&t=FYDFyjY4fB7zOlku-0).

![alt text](Images/Journal/figjam.png)

And we are still searching but that's it for these 2.5 hours.

### Recording links:
- https://lapse.hackclub.com/timelapse/BbDoTyLWUVCc
- https://lapse.hackclub.com/timelapse/BIIMvZWpS5dI

## Day 1 [![@ZIZO932](https://img.shields.io/badge/@ZIZO932-d97706?style=flat-square&logo=github&logoColor=white)](https://github.com/ZIZO932)

- **Date:** 14/9/2026
- **Total hours spent:** 2 hours

### Entry:

First day working with Nader horray i guess, it feels weird discussing the same project with someone else. We brainstormed for a bit then decided to build WALL-E a fully autonomous robot i think we would work on it for the whole 8 weeks. Nader started a figma and sent it to me so i started preparing the mind map i guess.
I began looking for already made clones to get the idea and understand what are we gonna do i found this project on instructables [2008 Clone](https://www.instructables.com/Build-an-autonomous-Wall-E-Robot/) it didnt offer much actually most of the electronics used were outdated and the functions of the robot itself isnt that good. 

![alt text](Images/Journal/2008%20walle.png)

Actually the design of it is quite good however i found another clone that is way better and way wayyyy more complex. [The main clone](https://www.youtube.com/watch?v=r7WV-IAMnDo)
This version is way better regarding the 3d model it uses 7 servos for arm, neck, and eyes.
Altough i think there will be some changes in the design i want to make however this is a very good start.
![alt text](Images/Journal/Walle%20.png)

### Recording links:
- https://lapse.hackclub.com/timelapse/B3YAmoDpvFuT
- https://lapse.hackclub.com/timelapse/6B3niGL5X6WF

------------------------------

## Day 2 [![@Nadoooor](https://img.shields.io/badge/@Nadoooor-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/Nadoooor)

- **Date:** 15/9/2026
- **Total hours spent:** 2.3 hours

### Entry:

WO, umm the second day, Well i kept searching for the remaining things that we need to add in the circuit and the firmware.

Searched for the things we will add without copying, like the ROS2, and the Isaac sim from Nvidia. 

the IMU sensor, and tid up the figjam.

um, for the Isaac sim, i was searching on how we will connect all of that in a simulation 'cause we don't know how to use ROS2 without buliding IRL, So i got many options but choosed Isaac sim 'cause it is from Nvidia and i have an Nvidia graphics card so it will be helpful. 

Also found something called Omnigraph nodes, it is something like gamemaker's nocode programing system, it uses nodes like it. and we can make custom omnigraph nodes to make them communicate with the ESP for examble. 

![alt text](/Images/Journal/Isaac.png)

After finding out about the simulation and the ROS2, i also started searching more about the sensor, and what are we missing.

Found that we can use an IMU, and also 2 ultrasonic, one from the back and one from the front.


and polished the figma a lil. 

![alt text](/Images/Journal/Sensors.png)

And that's if for this figjam (my part), here you are the full figma.

![alt text](/Images/Journal/Fullfig.png)

And after that, i started my kicad project and started make some pages and adding some components to the ESP32-s3 page, but i stoped after that and will continue in the next session.

### Recording links:
- https://lapse.hackclub.com/timelapse/Nfs9XLhcbCvm

## Day 2 [![@ZIZO932](https://img.shields.io/badge/@ZIZO932-d97706?style=flat-square&logo=github&logoColor=white)](https://github.com/ZIZO932)

- **Date:** 15/9/2026
- **Total hours spent:** 3.2 hours

### Entry:

I started this day with reviewing the last video and making a full mind map to using figma i started with the Eyes components and connection as shown in the image in which it the left eye would hold the camera with the pi zero 2w i thinkk .... i hadnt get quite sure about it yett actually. The right eye would hold the microphone and thats it, for the movement im using two servos for the movment of the right and left eye up and down it would move in cicuilar motion.

![alt text](/Images/Journal/Eye%20map.png)

For the track and movement that where it gets tricky in which it uses alot of parts to form the whole motion not the simple one which is two gears and track connecting them this one forms the shape of a triangle in which there are three gears with a track around it the track itslef is formed from small parts conncted to each other with smaller connectores 

![alt text](/Images/Journal/Track.png)

The neck uses two servos one for the y-axis and one for the x-axis which acts like a robotic arm and the body itself isnt that hard to be honest i just need to make sure that there is space for the pcb mounting and screen space on the front as well as an open and close compartment.

![alt text](/Images/Journal/Body%20and%20neck.png)

This is the whole [figma](https://www.figma.com/board/f0VK2TiKBMFvHDcY7YVH4b/WALL-E?node-id=0-1&p=f&t=AjgSqVmfp2gSIqVG-0)

### Recording links:
- https://lapse.hackclub.com/timelapse/i-zrSsbCG7CH
- https://lapse.hackclub.com/timelapse/cxqHd1hT7iQd

------------------------------

## Day 3 [![@Nadoooor](https://img.shields.io/badge/@Nadoooor-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/Nadoooor)

- **Date:** 16/9/2026
- **Total hours spent:** 5.4 hours

### Entry:

UHHH, well i took the whole 5 hours today to finish this week quickly so i can SIP (Study in peace). 

Ummm, OKkk i started with the ESP32-s3 in the schemaitc, and tbh, i did this before, i was about to replicate it slowly but naah, i just copied it from my old project.

<img src="https://cdn.hackclub.com/01a0aff7-8101-70a4-83af-7b7c80666e64/Screenshot_2026-09-17_182312.png" alt="Screenshot_2026-09-17_182312.png" width="700">

So after that, i started with the amplifier module, as i said before (ig) that i need to impliment all the modules in the PCB, like fully integirated and not just modules, So i started searching for the amplifer schematic everywhere, and found two option.

stereo and mono, but i prefered the stereo tbh, so i got the PCB and Schem from adafruit. and tried to reverse engineer it to catch all the components. 

And vola i got it done.

<img src="https://cdn.hackclub.com/01a0b005-534a-712c-bfe4-901963a76ba8/Screenshot_2026-09-17_183038.png" alt="Screenshot_2026-09-17_183038.png" width="700">

it wasn't easy tbh, as i needed to lookk into the three images of this amplifer (PCB, Schematic, and even the 3D & IRL component).

As there were many smd components that i don't know where they are like this 2 pads solder jumper.

<img src="https://cdn.hackclub.com/01a0b011-6332-76bc-91a4-87be921befa1/image__4_.png" alt="image__4_.png" width="100">

After that I started a new recording 'cause we wanted to calculate how so far we reached.

I finished the second channel amplifer and this is the FULL ampliifer image.

<img src="https://cdn.hackclub.com/01a0b012-61a3-78d0-a87f-2dd1a2fa7742/Screenshot_2026-09-17_185300.png" alt="Screenshot_2026-09-17_185300.png" width="300">

After the amplifer, i started working on the DC motor driver, BRUUUUUUh i took so much time trying to figure out what iam facing.

I really didn't find any clear PCB design of it but i found a Schematic, and also the IRL component from the back and the front.

This component FR made me reverse engineeer hardware, i really took so much time trying to figre out how it works. 

But the surpirse was that i was thinking for this whole time that it is dual channel Motor driver, and found out that it is just one channel, and i was super overwhelmed. so basicly i just made its schematic too and duplicated it. so i got this final version.

<img src="https://cdn.hackclub.com/01a0b013-d7e5-795d-a9b5-25dd7b88fc72/Screenshot_2026-09-17_185433.png" alt="Screenshot_2026-09-17_185433.png" width="600"> 

After i finished this component i reached my 10 hours for this week, so YAYYAY iam gonna study finally for the rest of the week.

That's it, thx.

### Recording links:
- [Finished another Amp & DC motor drivers · 2h 12m · Sep 16, 2026](https://lapse.hackclub.com/timelapse/Qo54ww1bt61t)
- [Finished ESP & 1 amplifier · 1h 58m · Sep 16, 2026](https://lapse.hackclub.com/timelapse/P7H9uDIHuwvh)

## Day 3 [![@ZIZO932](https://img.shields.io/badge/@ZIZO932-d97706?style=flat-square&logo=github&logoColor=white)](https://github.com/ZIZO932)

- **Date:** 16/9/2026
- **Total hours spent:** 1.25 hours

### Entry:

I finished the figma mindmap so decided to go for the next stage which is 3D modeling, i actually was thinking yeah it cant be that hard i quickly changes my mind after i decided to start modeling one of walle's eyes.(ONLY ONE !!) i was in a huddle with nader at least i wasnt alone when i was crying. I spend the whole hour figuring out the dimensions of the eye where the clone i was following isnt listed as open source so there were no way i can figure out the dimensions without estimating it.
<img src="https://cdn.hackclub.com/01a0b12d-5377-7f85-971c-4b76afc37132/Screenshot_2026-09-17_190215.png" alt="Screenshot_2026-09-17_190215.png" width="720" height="720">


  Howeverrrr, he listed the 3md file which gave me a clue about the scale there was no way i could have figured that on my own. So i opened onshape and began invistigating the 3d files and i got to a point where i was pretty sure about the dimensions of the eye. After sometime i skipped the eye design and got to one of body sides.

### Recording links:
- [3d model start · 1h 25m · Sep 16, 2026](https://lapse.hackclub.com/timelapse/R1QRREZ-F8Nh)

------------------------------

## Day 4 [![@ZIZO932](https://img.shields.io/badge/@ZIZO932-d97706?style=flat-square&logo=github&logoColor=white)](https://github.com/ZIZO932)

- **Date:** 17/9/2026
- **Total hours spent:** 0.4 hours

### Entry:

Yesterday i was stressing about the eye dimensions what so ever, i found that i can change the 3md file to stl so i can open it using solidworks, so i decided to open the file on solidworks and measure out the dimensions i needed so i can design my own walle eye.
I decided to use in connecting parts with each others M3 screws with a dimensions of 5 ml for the head 3 ml for the rest of the screw and a total length of 15ml this is supposed to be perfect i guesss we will seee. I also took a look at the 2008 walle where the design is impressive and i decided to add my touch in the eye. i just hope that all parts would be good to assemble. i finished the huddle with nader after this i think this is it for this week. 
<img src="https://cdn.hackclub.com/01a0b12b-21c1-7f95-ab33-808b6056448c/Screenshot_2026-09-17_190210.png" alt="Screenshot_2026-09-17_190210.png" width="1280" height="1280">

I LOVE WALL-E

### Recording links:
- [left eye finish · 40m · Sep 17, 2026](https://lapse.hackclub.com/timelapse/tFEgx5JB15S5)

------------------------------
