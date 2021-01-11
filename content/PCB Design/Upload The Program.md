---
title: Upload the Program
weight: -7
---
### Now that you have a finished board in your hand we are going to upload a code into the embedded microcontroller that will manipulate the LEDs array and display patterns on them. 
### To complete this task, you will need to download the latest version of Arduino IDE from theirwebsite, FTDI cable, your board and a programmer. 
### In our case we will use ATMEL ICE programmer along with the FTDI to USB converters available in the Lab.
 
### Luckly You wouldn't Write the Code By your self, I will give you the code 
```https://drive.google.com/file/d/1NvWuHSVEFNakQHMrkzQmeVt3Iz50cATd/view?usp=sharing```
____________________________________
#### Download the latest Arduino IDE from their website 
```https://www.arduino.cc/en/software.```
#### Arduino IDE naturally doesn’t support the microcontroller we are using in the board, so you
#### should add support for our microcontroller ATtiny45. The first step is to add a link to the support package by going to file->preferences->Additional Boards Manager URLs then paste the
### following link :
```https://raw.githubusercontent.com/damellis/attiny/ide-1.6.x-boards-manager/package_damellis_attiny_index.json```


[![Example bundle menu](/media/UTP1.png)](/media/UTP1.png)


#### The next step is installing the support package by going to tools->Boards->Boards Manager
#### then search for attiny and click install.

#### Now we have the Arduino IDE supports the microcontroller we are using. 
#### The next step would be setting up the controller and the programmer settings. 
#### Go to tools->Boards->ATtiny
#### microcontrollers->then select Attiny25/45/85. The next step go to tools->processor-> then select
#### ATtiny45. Then go to tools->clock-> then select internal 8 MHz. The final step is configuring the
#### programmer by going to tools->Programmers-> then select Atmel ICE (AVR).


[![Example bundle menu](/media/UTP2.png)](/media/UTP2.png)

#### Now the Arduino IDE is fully configured and we are ready 
[![Example bundle menu](/media/UTP4.png)](/media/UTP4.png)

#### and Now click on Sketch and then click on Upload Using Programmer 

[![Example bundle menu](/media/UTP3.png)](/media/UTP3.png)

#### and here is our PCB Yeah 
[![Example bundle menu](/media/UTP5.png)](/media/UTP5.png)
