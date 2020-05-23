# RadiositySolver
Radiosity solver for CS4247 (Graphics Rendering Techniques) at NUS

Radiosity solution is using progressive refinement radiosity computation with hemicube solution.
Each scene is devided into quads and each quad colour is stored in the colour buffer. 
With each iteration, we pick the brightest quad, shoot its power and updated the gatherer quads.

## Scene 1 - Cornell box 
<img src="https://github.com/Futuramistic/RadiositySolver/blob/master/cornell_box_1.PNG">
<img src="https://github.com/Futuramistic/RadiositySolver/blob/master/cornell_box_2.PNG">
<img src="https://github.com/Futuramistic/RadiositySolver/blob/master/cornell_box_3.PNG">

Colour bleeding (diffuse-to-diffuse interaction) can be seen on the sides of the boxes

## Scene 2 - Room model
<img src="https://github.com/Futuramistic/RadiositySolver/blob/master/new_model_2.PNG">
<img src="https://github.com/Futuramistic/RadiositySolver/blob/master/new_model_3.PNG">
