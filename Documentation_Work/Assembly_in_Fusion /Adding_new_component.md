# Changes to be done 
The first step in Assembly is adding a new component.Eventhough it doesnt look complecated, one very import step before starting creating a sketch must be complited. ASSIGN NEW SYSTEM OF COORDINATE!

For example lets take a look at adding a new component on a piece of Chelonia's aluminum extrusion:
1             |2
:-:|:-:
<img src="../Assembly_in_Fusion /Images/AddExis.jpg"  width= "100%"> Open the cloud -> right click -> Insert into current design.\n Allign if needed. | <img src="../ConnectionParts/images/Fusion1a.jpg"  width="100%"  > Open it as a project (go to "File" and "Open") on your personal Fusion account.
3           |4
<img src="../ConnectionParts/images/Fusion2.jpg"  width= "100%"> Click on the upper surface inside  the part with the hole were the nut will be inserted. Go  with right click to "Create a new Sketch"  | <img src="../ConnectionParts/images/Fusion3.jpg"  width="100%"  > To make the whole body of hte connecting part invisible and just see the line of the surface, Go To " "Create" and click on "Project/Insert" and choose the surface.
5          |6
<img src="../ConnectionParts/images/Fusion4.jpg"  width= "100%"> Create three lines and use the measurements taken from the new nut used (I used a tolerance of 0.5 mm on each side). Make sure the contrains are right (parrallel lines).  | <img src="../ConnectionParts/images/Fusion5.jpg"  width="100%"  > Finish the sketch and got to "Extrude", then click on the surface area created by the 3 lines and extrude it with the "Joint" function (see window on the right side)
7         |8
<img src="../ConnectionParts/images/Fusion6.jpg"  width= "100%"> Now we want to remove the small edges created by the extrusion. Start a sketch on the plane of the connecting part.  | <img src="../ConnectionParts/images/Fusion7.jpg"  width="100%"  > Create a simple line.
9        |10
<img src="../ConnectionParts/images/Fusion8.jpg"  width= "100%"> Finish the sketch and Go to "Offset Plane" and create a "Plane at Angle" click on the line and have a look if the create plane is parallen to the x-y-plane of the connecting part. If not, adjust the angle  | <img src="../ConnectionParts/images/Fusion9.jpg"  width="100%"  > Create a sketch on this plane and create a simple rectangle were one edge is dirctly on the face of the connecting part.
11        |12
<img src="../ConnectionParts/images/Fusion10.jpg"  width= "100%"> Extrude the rengle and use the "Cut" function of the extrusion. | <img src="../ConnectionParts/images/Fusion11.jpg"  width="100%"  >Then extrude the ring face to create smaller hole for the bolt ( do not forget the "Joint" Function)
13       |14
<img src="../ConnectionParts/images/Fusion12.jpg"  width= "100%"> Extrude the rengle and use the "Cut" function of the extrusion. | <img src="../ConnectionParts/images/Fusion13.jpg"  width="100%"  > Last step for the 3D printing is to export the part as an .stl so you can import it into a slicer software. 


LOL TEST
