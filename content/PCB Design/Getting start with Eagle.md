---
title: Starting With Eagle
weight: -10
---
#### In order to design both schematic and PCB layout of the board I used EAGLE software. 
#### which can be downloaded from 
[Download Eagle](https://www.autodesk.com/education/free-software/eagle)
#### if you have a AUTODESK student account.

#### After installation was complete I added a new schematic file. A schematic is a drawing representing connections between electronic components . 
#### Then I should add the components I need to use in my board, so I downloaded fab.lbr library
[Download Components](http://fab.academany.org/2018/labs/fablabirbid/students/israa-rabbaa/ElectFiles/fab.lbr)
#### Then from the Library bar, select Open library manager and browse the location of the downloaded library then it will be automatically added to the component list.

### Using Eagle 
#### Eagle is a simple software , you wouldn't need much to learn it , However what you nedd is to practice on it , over and over to become master on it.
#### You can see this video to see how to made a PCB layout
[CLICK HERE](https://drive.google.com/file/d/10_0TKVjUORiP6gC0jGy6ljAa1wVREkyD/view)

___________________________________________________________________________

#### First-time users of EAGLE will be greeted with the rather confusing Eagle Control Panel. You probably expected to see a direct-to-schematic approach, but no, this isn’t a very beginner-friendly application (but it’s very rewarding indeed, so stay tuned).

{{< columns >}}

<--->
[![Example bundle menu](/media/GSE1.png)](/media/GSE1.png)
            Eagle Control Panel
<--->
{{</columns>}}


#### Start by going to File>New>Project. A new project should appear. You can give it a name, but I chose not to.

#### Now go to File>New>Schematic. This will create a new schematic in the project that was currently opened.


[![Example bundle menu](/media/GSE2.png)](/media/GSE2.png)



#### You will be greeted with another less-than-intuitive window where there is seemingly no way to start drawing a schematic.
#### You may have clicked the Add Part tool, only to be greeted by a window that shows no components to be added, and probably tried another way, as I did when I first started learning.


[![Example bundle menu](/media/GSE3.png)](/media/GSE3.png)


#### In earlier versions, this was more complicated but now you only need to click the Open Library Manager button and go to the Available tab.

#### You may choose to download all the available libraries, but if you aren’t keen on waiting for 412 (as of May 2019) libraries to download, I recommend searching for the libraries by SparkFun as well as the libraries rcl, linear, transistor-fet, transistor-npn, transistor-pnp, and transistor-power, all in lbr format.

#### The libraries by SparkFun are easily the most useful libraries for fiddling with Arduinos, Raspberry Pi, smart home systems, and most hobby electronics involving microcontrollers.


[![Example bundle menu](/media/GSE4.png)](/media/GSE4.png)

