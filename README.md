# PlasticPushing
This is a analytical/research specific repo for printing various plastics on a voron 3d printing machine

Introduction
I have been 3d printing for almost five years and have only owned two types of printers. a cartisian printer from Creality3D and my custom VoronDesign v2.4. Since I completed the build on the V2.4 I have not stopped printing and want to share my learnings with the rest of the community. 
Lets talk the basics first, You need to undertand that each printer and your environment will affect everything that is mentioned in this post. Since 3d printing is a skill that takes several hours to be proficient, all of these settings will have some deviation for your tuning.
Second, this guide will focus more on tuning each filament manufacturer [See xlsx document]. Additonally, this is a repository for color palettes so enjoy the splurdge of plastics!
third please visit Ellis print tuning guide as his details are far more specialized in ABS and Voron printers as a whole. I would recommend especially you read the first lines because they will apply with all plastics, not just ABS or Voron printers!
https://github.com/AndrewEllis93/Print-Tuning-Guide

1) import my base configs, some settings may need to be changed for your printer size/height or other parameters that are specific to you.

2) (run a temperature tower) you can generate them in SuperSlicer or download and import into your slicer. If there are .3mf files in the repo, you can get them easily imported into your slicer. {WIP .3mf file needs added} NOTE: some people will be using seperate slicing software i.e. cura, simplify3d, ect.. this repo currently does not support those slicers. 

3) (run pressure advance for filament) - See .xlxs file for parameter ranges

4) (run Extrusion Multiplier test) - See pre-configured EM .3mf (ABS PROFILE), PLA, PETG, CF filled filaments will come at a later date.

5) (run a ADXL board from the Stealthburner toolhead attachment)

