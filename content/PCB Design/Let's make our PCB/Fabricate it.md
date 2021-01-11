---
title: Fabricate it
weight: -18
---

### in this part we will fabricate the PCB using Modela Melling Machine 

### This part is fun and EAsy to make just Follow the instructions 

#### Now we get our hands involved ! The milling process is done on a large piece of copper and
#### using two endmills : 1/64 for milling the traces and 1/32 for cutting the board. The steps you
#### need to follow is as follows:

___________________________________
#### - Open the Holes Photos and invert the colors on Gimp 

[![Example bundle menu](/media/FTPCB1.png)](/media/FTPCB1.png)

#### 1. Setting up the copper board.
#### 2. Fixing the copper board to a wood sacrificial layer.
#### 3. Placing the 1/64” endmill.

[![Example bundle menu](/media/FTPCB2.png)](/media/FTPCB2.png)

#### 4. Setup the zero point in X, Y and Z.
#### 5. Using Fab modules to generate the toolpath for trace milling using 1/64” board.
#### 6. Send the toolpath to the machine
#### 7. Replace the 1/64” endmill with 1/32” endmill.
#### 8. Setup the zero point in X, Y and Z.
[![Example bundle menu](/media/FTPCB3.png)](/media/FTPCB3.png)

#### 9. Using Fab modules to generate the toolpath for the cutting process.
####  َ10. Send the toolpath to the machine.

[![Example bundle menu](/media/FTPCB4.png)](/media/FTPCB4.png)
__________________________________


For setting up the machine, we would recommend that you watch these videos:

```https://www.youtube.com/watch?v=XdamEhs2RIk&list=PL-xEsC0ZUCUM42QNHaOOdoOwYg0j251dU&index=1```


Regarding using Fab modules, you would need to learn how to start the local fab modules
server on the PC. You may ask the lab supervisor on how to do that. To generate the toolpath
and send it to the machine, you should follow this video :

```https://www.youtube.com/watch?v=mySjdHuCHJE```

{{< hint >}}
**There are some corrections to the videos**
1. Our machine is MDX20.
2. Instead of saving the toolpath, press send to directly execute the toolpath.
3. You may need to put values in the X, Y field in case if you want to start milling from a
different point other than 0, 0.
{{< /hint >}}

