<div id="top"></div>


<!-- ABOUT THE PROJECT -->
## Interactive Painting Program

A really simple canvas painting program that does not use any third-party libraries (such as jQuery, etc.)

Program renders 800px by 800px canvas where you are able to draw, pick brush sizes, pick color, and use a few more features create your masterpiece.
I will be including the changelogs and test log here.


### How to Run the Program

1. Download/Fork the project single project file.
2. Open the file using a browser, such as Google Chrome.



<!-- CHANELOG -->
## Changelog

29/10/2018 v1.01

Canvas size is now 800px wide and tall
Template color selectors have been fixed and 4 of them are added, total 8 
Canvas reset button has been fixed
Reset button has been renamed to "Clear All"
Eraser button has been added, it is the same as background color

30/10/2018 v1.02

Clear All and Eraser buttons have been repositioned
As the mouse hovers over the a button, it is now highlighted in red

31/10/2018 v.1.03

4 Brush sizes have been added
An indication box have been put next to the brush sizes
As mouse moves over pressable elements, crosshair will transform to a "pointer"

1/11/2018 v.1.04

Preview circle has been added, to display the currently selected color
Starting paint color is now the first color box from the left
		
2/11/2018 v1.05

Selected brush size will now be highlighted
Clear all tool can now change the background color to the currently selected paint color
Current background color can now be identified by the background preview circle
	
3/11/2018 v1.06

Eraser will now act upon the changed background color
Erase button will work with CTRL key pressed while drawing
Painting mode and Erasing mode will be displayed
Blend tool has been added with a preview box and 3 sliders representing red, green, blue
Ability to use the blend tool color



<!-- TESTLOG -->
## Testlog

Format:
Test Date, Use & Operatins No (1-6), Description, What did you test, Results, Reflections			

29/10/2018

Paint Color Tools (4), Selected Color and Color(1-8), if the identified color is selected onclick on the certain tool, PASSED, simple for now, later on preview feature (of the currently selected color) will be implemented

29/10/2018

Clear Tool (6), Clearing Canvas, this method will clear wanted object (canvas) in the given rectange therefore clears the canvas entirely, PASSED, simple for now, later on Clear Tool will change the background color to the picked tool

29/10/2018

Erase Mode (2), Erase (Paint background color), this tool will not "erase" but paint on the canvas with the selected background color, PASSED

31/10/2018

Brush Sizes (3) and Paint Mode (1), 4 different brush sizes and alligning paint with offsets, created 4 different tools and tried to keep brush sizes in one function however it doesn't work with if statements for each different offset, FAILED, making 4 different functions will not appear practical but will be practical in terms of working out the iOffset

31/10/2018

Brush Sizes (3) and Paint Mode (1), 4 different brush sizes and alligning paint with offsets, 4 functions have been created and hooked to an individual button so after a button is selected it should change to brush size regarding to the values in the function, PASSES, may appear unorganized this way but is more practical for me to improve if necessary

1/11/2018

Color Selection (4), Preview Box, a new function has been implemented to display the picked color called "fnDesignatedColor_EG", PASSED, it also displays when the eraser is selected as the white background color which might need an improvement

1/11/2018

Brush Size (3) and Paint Mode (1), 4 different brush sizes and alligning paint with offsets, tried to keep them in one function but the problem is when this single function is expecting 2 parameters which are width and height it is challanging to change offsets for each different brush size, FAILED, can't find a solution after 6+ hours on brush size doesnt look promising while keeping it in one function

2/11/2018

Brush Size (3), 4 different brush sizes and alligning paint with offsets as well as highlighting the chosen brush size, PASSED, 4 different functions works perfectly

2/11/2018

Clear Tool (6), clear tool changes the background color to the selected color and is hooked to the background preview box, PASSED

3/11/2018

Erase Mode (2), function has been improved to act upon the newly selected background color and erase upon that, PASSED

3/11/2018

Erase Mode (2) and Paint Mode (1), text will now display which mode is being used by the user, PASSED

3/11/2018

Blend Tool (5), 3 sliders (rgb) will form a color displayed a unique preview circle for that and users will be able to select this color to paint, PASSED




<!-- CONTACT -->
## Contact

Erol Gelbul - [My Website](http://www.erolgelbul.com) - erolgelbul@gmail.com

Project Link: [Painting Program](https://github.com/ErolGelbul/interactive_painting_program)

<p align="right">(<a href="#top">back to top</a>)</p>
