# TouchDesigner-MouseControl
TouchDesigner 088 component to control mouse actions using Python ctypes

##Build and Version
This tool requires 'Custom Parameters' functionality within TouchDesigner (Build 45000 and above). It was created, and is stable, in 64-bit build 62070.

##Installation
1. Move the ```mouseOut``` folder into your project root folder.
2. Add the ```mouseOut.tox``` component into your project.

##Pre-requisite Python files
All pre-requisite Python libraries are included as a part of the nVoid Twitter Tools folder package. 

##Usage
This COMP uses extensions to control the mouse position and left, middle, and right buttons.

Methods:
- MP(x, y)
  - sets the mouse position
  - requires values within the range of 0 to 1
  
- LeftDown()
  - presses the left mouse button down
  
- LefUp()
  - releases the left mouse button

##Troubleshooting:
If you find an issue, submit a pull request or post an issue on this repo. 

##Attribution
If you use this in one of your projects, feel free to give us (nVoid) a shoutout or just let us know what you're up to! 
