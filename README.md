# TouchDesigner-MouseControl
TouchDesigner 088 component to control mouse actions using Python ctypes

##Build and Version
This tool requires 'Custom Parameters' functionality within TouchDesigner (Build 45000 and above). It was created, and is stable, in 64-bit build 62070.

##Installation
1. Add the ```mouseOut.tox``` component into your project.

##Usage
This COMP uses extensions to control the mouse position and left, middle, and right buttons. It allows the control of the mouse even when the TouchDesigner window is not in focus.

###Methods:
- MP(x, y)
  - sets the mouse position
  - requires values within the range of 0 to 1
  
- LeftDown()
  - presses the left mouse button down
  
- LeftUp()
  - releases the left mouse button
  
- MiddleDown()
  - presses the middle mouse button down
  
- MiddleUp()
  - releases the middle mouse button

- RightDown()
  - presses the right mouse button down
  
- RightUp()
  - releases the right mouse button
  
- LC()
  - clicks the left mouse button, so it calls LeftDown() then LeftUp()

- MC()
  - clicks the middle mouse button
  
- RC()
  - clicks the right mouse button
  
###Custom Parameters
The custom parameters can also be used to set the mouse position and trigger the mouse button events.

The mouse position can be set using the ```X Position``` and ```Y Position``` sliders. Left, Right, and Middle click call the LC(), MC(), and RC() extensions.

If there is a need to click-and-drag, one would use the ```Left Toggle```, change the ```X Position``` and ```Y Position```, then disengage the ```Left Toggle``` to release the mouse button.

##Troubleshooting:
If you find an issue, submit a pull request or post an issue on this repo. 

##Attribution
If you use this in one of your projects, feel free to give us (nVoid) a shoutout or just let us know what you're up to! 
