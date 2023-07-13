# Proxxon MF70 CNC
CNC conversion for the Proxxon MF70 based on 3D printed files.
Electronics embedded in Z-axis column !

![Machine](/Pictures/20200807_135809379_iOS.jpg)

If you like then please

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://bmc.link/nic6911w)

## BOM
Arduino UNO  
GRBL Shield w. 3 x drivers  
Braided cable sleeving  
Double adhesive tape for cable-tie mount  
3 x Alu flex coupler 5x5 mm shafts and outer measurements: 19x25mm  
E-stop button for 16mm panel cut-out. 23.5mm diameter button  
6 x F5-12M bearing  
3 x 7 mm push button switches for endstop SPST PBS-110  
12 x M3x6 for motor mount  
6 x M4x35 for mounting brackets  
6 x M4 SL nut  
3 x small screws for mounting Arduino  
3 x NEMA 17 stepper motors  
Wires and connectors as needed for switches and motors  


Printed parts:  
6 x cable_tie_mount  
3 x spacer_xyz  
1 of each of the remaining files  

## Software
GRBL and OpenBuilds Control software. My GRBL settings can be found in "grbl-settings-backup.txt"

## How To
Print the parts  
Measure up lengths of wires for motors and switches (make them somewhat longer than needed to be sure) and solder things up to get the extended cabling needed  
Disassemble the x, y and z-axis of the proxxon  
Remove the xyz handles from the lead screws  
F5-12M bearings goes in both ends on the x and y-axes and on the z-axis it there is one on both sides of the printed z-axis mount  
Only the original proxxon plastic part on the motor side is replaced on the x and y-axes  
A grooving in the 3D printed parts for the x and y-axes takes the metal plate from the original proxxon part  
Mount motors and end-switches on the x and y-axes motor mounts  
When a bearing has been placed in both ends of the x and y-axes the the motor mounts can be added to the x and y-axes (remember spacer and flex coupling)  
Make sure there is a little tension on the flex-coupler up against the spacer that pushes on the F5-12M bearing  
  
This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

Find more of my work here:  
https://youtube.com/user/wan46696  
https://www.instructables.com/member/nicengineering/