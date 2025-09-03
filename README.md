# Final Project
## Paint App - Adelina Gutic

This document will break down all of the interactive elements that are part of this final project!

-----------------------------------------------
Key Board Shortcuts:
'1', '2', '3', and '4' save the current brush color to the respective "saved color" button. Clicking these buttons on its GUI will change the current brush color back to the saved one.

Holding 'b' while changing the RGBA sliders will change the background color.

's' saves the current window as a timed screenshot that can be found in the bin folder of this project.

'c' clears the window.

----------------------------------------------
GUIs:

"Brush Parameters" allows you to change the size and RGBA values on any current brush using sliders.

"Brush Shape" allows you to change the shape of your current brush. Since you can only hold one brush shape at a time, these are buttons!

"Freeform Brushes" allow you to be more precise with your brush strokes by changing the brush style completely. Using polylines, you can use freeform brush strokes with the 'curved' brush, or straighter strokes with the 'straight' brush.

"Saved Colors" allow you to access any previously saved colors by maniulating the RGBA sliders when the button is pressed. Hoolds four different colors!

"Audio Toggle" manipulates the brush size by taking in audio input and reading the "loudness", or RMS value, of the audio into the size slider. Makes for some very cool effects!

------------------------------------------------
Image Background:
Inputting 'none' into the terminal allows you to open the window on a blank white background. Otherwise, when inputting an image name, ensure that the image is present within the bin folder of the project, otherwise it will not read it! Png images allow you to color in images quite easily since they are mostly transparent, while jpg images will go through a mesh to cut out the most intense colors of the image and ensure a unique coloring experience!
