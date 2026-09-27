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

## Day 4 [![@Nadoooor](https://img.shields.io/badge/@Nadoooor-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/Nadoooor)

- **Date:** 22/9/2026
- **Total hours spent:** 1.6

### Entry:

Uhh, ok in these 1.6 hours,
i Made a great work tbh in the schematic, ii worked on the servo controller and finished it all

So iam gonna talk here about how exactly i worked on it and where was the hard points. (i see that the servo controler was the hardest so that's why iam gonna talk more about it here.)

i searched for the servo controller on adafruit guides, and i found it there with its schematic and pcb and 3d model, just like the Amplifier. 

<img src="https://cdn.hackclub.com/01a0e3d2-12a4-7218-ab9a-74cbec334a7d/Screenshot_2026-09-27_195746.png" alt="Screenshot_2026-09-27_195746.png" width="700">


So, i started reading the schematic how it is made and tbh it wasn't that bad, not like the Amplifier, like i learned from the amplifer and got its hiddens and made it.

So i quickly got all the info and understood the schem, and then started making it in the actuators page in my kicad project.

Well, i found it in kicad default libraries and i added it, but when i added it, i saw that it was for PWMing LEDs, so i was kinda overwhelmed on how it should work with servos. 

But lol after i searched i got that it is normal that PWM can control LED brightness or Servos, i was kinda dump here but yay learned it. 

Anyways, i added a text on the symbol saying that it is controling Servos here not LEDs.

<img src="https://cdn.hackclub.com/01a0e3d3-284e-7e93-95a4-206199e91f84/Screenshot_2026-09-27_200015.png" alt="Screenshot_2026-09-27_200015.png" width="400">

after that i searched about the rest of the components like capacitors and resistors and added them, but i saw a weird looking symbol that i didn' see before.

<img src="https://cdn.hackclub.com/01a0e3d3-dd5e-702e-87df-cf5d158f2af9/Screenshot_2026-09-27_200037.png" alt="Screenshot_2026-09-27_200037.png" width="500">

Well i got that it was a reverse voltage protection circuit, so i searched about the component and found its name on kicad "Q_PMOS_GDS"

after finishing its circuit, the last thing was the pins of the servos, so i started making one 12 pins and then copied it and pasted three more times, and i got this beauty. 

<img src="https://cdn.hackclub.com/01a0e3d6-a902-756f-b264-592c366ae0f3/Screenshot_2026-09-27_200049.png" alt="Screenshot_2026-09-27_200049.png" width="400">

after finishing it, i added labels for the SDA and SCL and voala i finished the servo controller. 

<img src="https://cdn.hackclub.com/01a0e3d7-a557-74b8-bbe8-d3842b870c77/Screenshot_2026-09-27_200057.png" alt="Screenshot_2026-09-27_200057.png" width="500">

TBH i was super afraid from this one specificly, i thought it is so big and has many things but it was easy (ahem ahem, in the Schematic not the PCB yet :skull)

### Recording links:
- [Made the Servos Controller · 1h 19m · Sep 22, 2026](https://lapse.hackclub.com/timelapse/AyFFHhh8GsSA)

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

## Day 5 [![@Nadoooor](https://img.shields.io/badge/@Nadoooor-2563eb?style=flat-square&logo=github&logoColor=white)](https://github.com/Nadoooor)

- **Date:** 27/9/2026
- **Total hours spent:** 7

### Entry:

WOW, that was insane, ugh i don't know how i will journal all of these hours but duh, let's wrap it up.

Well, i continued working on the Schematic in this session, well, i nearly finished 95% of it.

I made MANYYY things, so i need to be kinda organized while writing ts, So iam gonna wrrite the big points downthere and than will take each point will talk about it.

1. I Started searching about the mic

    a. I got that i can use two

2. Searched about the camera
3. add hand sily made symbol for it with no pins.
4. searched about the 5v stepdown     
    b. gonna use two
5. got the resistors needed for 5v
6. edited the ESP32 pin labels, and made its page in the brain.
7. same for the RasPi
8. connected teh UART bridge between the Pi and the ESP.
9. Worked on the brain page pin distribution (it looks so awesome)
10. Made the same thing for the rest of the Pages
11. added a tft screen from my old project, to be like the dashboard or the screen under Wall-Es Eyes.
12. started connecting the screen to the raspi GPIO. 

WOW, these are so many points, anyways.

First, the camera. well this one was kinda super easy, but i just wondered how i will add it to the Schematic, so i just made a quick lil symbol for it with no connections, and then wrote on it that it is just a regular pi camera and also added the pi camera version.

<img src="https://cdn.hackclub.com/01a0e42a-0057-7815-94c5-f165a16a6a55/Screenshot_2026-09-27_213431.png" alt="Screenshot_2026-09-27_213431.png" width="300">

Second, well for the stepdown, this one was super important, as it will be used to provide voltage for the pi and the esp, but i didn't want to connect the servos to the same stepdown, as it will take so much current and also can make the logic circuit disturbt. So, i added two stepdown with the same module, and connected a +5V to one of them and another +5AV to the other, as +5V is separated from +5AV. and +5AV is for the servos.

<img src="https://cdn.hackclub.com/01a0e42a-043f-76a9-af8e-9dd0c789867f/Screenshot_2026-09-27_213504.png" alt="Screenshot_2026-09-27_213504.png" width="500">

Third, i knew that this stepdown has a variable resistor to control the output voltage, but for me i didn't want to change anything, so i searched about the specific resistor value and placed a static resistor instead, in that way it won't never ever exceed 5.2V or lower than it.

<img src="https://cdn.hackclub.com/01a0e42a-0017-7627-b8b4-d8c47b38d0d4/Screenshot_2026-09-27_213533.png" alt="Screenshot_2026-09-27_213533.png" width="200">

Fourth, i edited the ESP pin labels to be hierachy labels, so i can access it from the outer page (Brain page), and also i organized the page pins based on the ESP32-s3 module itself as it looks so cool tbh. also made the same thing for the pi and connected the UART bridge for both of them so they can communicate wiredly. 

<img src="https://cdn.hackclub.com/01a0e42a-02dd-720f-8458-80c67d495506/Screenshot_2026-09-27_213552.png" alt="Screenshot_2026-09-27_213552.png" width="500">

Fifth, The page of the brain in the main page, when i synced the labels i mean, i decided to make it as like as the QFP components, as it can represents the main proccessing unit and the brain of the system, So i added all the labels, and then started manageing and organizing them, i took two sides for the ESP32 GPIO and the other two for the RasPi GPIO. I made it superr cool tbh.

<img src="https://cdn.hackclub.com/01a0e42a-0325-71ed-bbf3-5653e874c882/Screenshot_2026-09-27_213612.png" alt="Screenshot_2026-09-27_213612.png" width="400">

and yeah made the same thing for the rest of the pages and ordered the labels in a good way. and bruuuuuh, this looks soooo awesooomeee, this is my first time to use pages this intensvly, i used just one before.

<img src="https://cdn.hackclub.com/01a0e42a-0275-7ad6-8746-486637d3895e/Screenshot_2026-09-27_213624.png" alt="Screenshot_2026-09-27_213624.png" width="500">

Sixth, while i was checking the pages, i got that i forgot about one, the Dashboard, well actually i didn't even make brainstorm for it, so i just added a TFT 2.8 spi display, it will be like Wall-Es sun display and battery info, and also just a button to cut the main power.

<img src="https://cdn.hackclub.com/01a0e429-fefc-73f8-95e6-fd176e238f34/Screenshot_2026-09-27_213638.png" alt="Screenshot_2026-09-27_213638.png" width="500">

after adding it, and syncing the dashboard page labels too, i searched about how i will connect it to the Pi or the ESP, and tbh ig connected to the Pi is better, as it can work on making the visuals instead of the weak esp. (dk ig so), So i connected it to the RasPi SPI pins, and also along with the touch. 

After that all, well bruuuh ig the mic and the speaker need some changes, as i searched and ig i can't connecct input and output I2S modules to the Pi at the same time. So i set this as a goal for the next session (or week). 

and yeah, that's it ig, i believe i got all the points in here. 
 
I hope i got this super well organized :cry.

### Recording links:
- [UGHH a lot and i don't rememeber · Sep 24, 2026](https://lapse.hackclub.com/timelapse/0kmRS9EgVi52)

## Day 5 [![@ZIZO932](https://img.shields.io/badge/@ZIZO932-d97706?style=flat-square&logo=github&logoColor=white)](https://github.com/ZIZO932)

- **Date:** 27/9/2026
- **Total hours spent:** 

### Entry:

This session i started with the second eye which i had to redo because mirroring it wouldnt work considring that so i needed to redo the eye by making more. i found when i finished the right eye that i forgot to add a hinge to connect the two eyes which will be connected with each other using a hinge conncetor.
I looked into it and saw the video again i found that i needed to make sure that the two of the holes are the same size to connect correctly however what i missed is that i needed to make the two parts which would hold the hinge in different places like for the right eye i would make it slightly forward and for the left eye i would make it slightly back so that when they are put next to each other they align perfectly and make it easier to use the hinge then after finishing the right and left eye i decided to go for the next part which is the inside of the eye. so what is the use of it ? 
it would be the place where they hold the mic sensor or module not decided yet, and the other eye would hold the camera we wanna use raspberry pi zero so i think a raspberry pi camera would be our choice i may need to ask nader later.
After finishing the inside part of the eye i decided to go for the rest of the eye to clarify:
walle's eye conisistes of small part and a big part that gives it the longtidunal shape which is very unique for walle the problem with the big part is that it needs to be designed to align perfectly with the small part and also offer space for adding sensors and wiring.
in this session i decided it was enough to stop here cause the big part woud take a lot of time so either i lock in now or just make it in the next session (lmao im writing this after i already finished the two sessions of the week) 
finally i prepared the files and made sketches for the rest of the parts 

<img src="https://cdn.hackclub.com/01a0e45a-c313-7ca1-9710-e2312b332e75/Screenshot_2026-09-26_120817.png" alt="Screenshot_2026-09-26_120817.png" width="1280" height="1280">

<img src="https://cdn.hackclub.com/01a0e45b-638d-7be7-bba7-3726e9fdddf3/Screenshot_2026-09-26_120830.png" alt="Screenshot_2026-09-26_120830.png" width="1280" height="1280">

<img src="https://cdn.hackclub.com/01a0e50d-d70a-78fd-9aa6-19fa3db71b35/Screenshot_2026-09-26_130841.png" alt="Screenshot_2026-09-26_130841.png" width="1280" height="1280">

### Recording links:
- https://lapse.hackclub.com/timelapse/RGJQpuucflLY

------------------------------
