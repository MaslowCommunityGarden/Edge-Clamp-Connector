### About the files in this repository: 

**Corner Connector v15.f3d:** The Fusion360 model uses a user defined parameter for "materialThickness" this may need to be changed for your application and in hindsight I probably should have set the file up differently with parameters for Material Thickness, edge lengths, angles (90, 105, 150); that way a user could just adjust those for what they want.

**edgeclamp-75.nc:** This was the NC g-code file that I used to cut the POC connector out of 3/4" (actually 23/32") CDX plywood. There is some optimization that can be done on this g-code; this is the first time I just Fusion360's CAM module to create g-code for the Maslow. 

**Construction:** 
1. To construct the clamp you will need to cut 2 outer pieces and 2 inner pieces (i.e. run the g-code twice)
2. Glue the 2 out pieces together and the 2 inner pieces. This is to double up the clamp; so if you are using 3/4" stock the resulting piece from gluing are 1.5" thick. 
3. Drill a hole that corresponds to your screw through the center of each part (like in the pictures). Countersink the nut if you want (this will allow you to use shorter screws, just leave enough material in there). 
4. Insert screw and nut. 
5. Clamp something together.
