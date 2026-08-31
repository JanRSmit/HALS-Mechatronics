# HALS-Mechatronics design

THE HALS (Holographic Acoustic Loudspeaker Scanner) Mechatronics design process documentation and 3D models Unlike code a physical device cannot be copied. So instead in this repository covers the design, construction, alignment and test process i followed. In this way it provides a path for others to follow and produce their own version of the HALS-Mechatronics.

HALS is composed of 3 main components:

·         Mechatronics design: This repository

·         Measurement s/w    :  [NFS](https://github.com/TomKamphuys/NFS) 

·         Postprocessing s/w  :  [lah-scanner](https://github.com/dfapinov/lah-scanner)

To be completed .

  

## The start

![](file:///C:/Users/JanRSmit/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)  
The design for me started in July 2025 with a rough sketch depicting a compartimented approach. The reason being that the DIYAUDIO thread "Klippel Near Field Scanner on a Shoestring" sort of came to a silent stand-still despite Tom Kamphuys efforts.
![Alt text](My-Starting-Sketch.png)

So i contacted Tom to start a collaboration where would do the mechatronics part and he the software part. A bit lateron Dimitri joined with his post-processing software.

Initially i published my approach on the thread in DIYAUDIO with an excel and pictures mostly. Recently we decided to post all on GITHUB. For me this is a learning curve ;-)

To be completed

  

## The breakdown into compartments

My approach started as a sketch, a modular approach so it can be taken apart for movement or storage and fit in a room of 3x5x2.4m . After some desktop research in possible concepts for moving a microphone around a still standing DUT, I decided to base my solution on rotating an arm carrying the movable vertical beam for moving the mic up and down.

To do this in a reasonable period I decided, again after some intense desktop research:

\-          A sturdy steel Tripod as base and central pillar.

\-          Use of V-slot concept profiles and assemblage parts.

\-          Stepper motors & reduction gear.

\-          Internationally available , purchasable parts where possible, like bearings, axle bars, heavy quality tripod, etc.

\-          From the CNC community the grbl based firmware and supported controller and motor driver electronics for the motions.

\-          For the rotating movement, a timing belt HTD3M 9mm belt, and for linear movement a GT2 9mm belt.

\-          A physical construction that can be taken apart in main modules for movement to different locations or temporarily storage.

\-          Where needed 3D printable parts using PETG, in this case Rapid PETG to reduce printing time.

### The breakdown:

\-          BASE (Foot & Main pillar):

\-          Rotating Drive:

\-          Hub-Arm-assembly:

\-          Z-axis-Mic-Assembly:

\-          STOOL: The DUT platform:

\-          Motion (Electronics-Motors)&Cabling:

\-          Operator instruction / manual

\-          To be completed


For each a separate folder is created containing:

\-          Decision list

\-          Pictures

\-          3D step files

\-          Assemby instruction/tutorial

As an idea of the actual HALS mechatronics size:
![Alt text](My-Starting-Sketch.png)
\-          Test tutorial/results

\-          3D print instruction

To be completed

#A preview of the actual machine now running measurements :
![Alt text](HALS-MECHATRONICS-2700-2300mm.jpg)
The circumscribing diameter is 2700mm, the height ~2300mm, the testobject shown is ~680mm high.

## Current Status September 2026
Now ~ 1 year later, the robot is being used for some 9 months now and still functioning fine and accurate!

Here a quite complete 3D model of the HALS robot. I just finished the models and the bills of material. Invluding fasteners, washers etc. Will do a check and then post the latest versions in tbe Github, with screencopies etc. Aim is end of this week.
The 3D is in fusion360 format. A nice feature of f360 is the isolate function, to see just one object, handy for exporting for 3D printing. Which i do in step format as the slicer i use reads step for generation of the printfile and does a better job than f360 meshing.
![Alt text](HALS-ROBOT-Sept-2026.png)
The controller case, powersupply for motors, and amplifier and any cabling for the DUT are not shown here.
But in reality it is like this::
![Alt text](Gear-underneeath-HALS-robot.jpg)
The cables at bottom of picture go to the hals computer (USB) and audio i/f (XLR).
