# How to make a new component
To start with Assembly, the first thing to do is introduce a new component. Although it might seem simple, there's an important initial step before diving into sketch creation<BR> <b>ASSIGN A NEW SYSTEM OF COORDINATES!</b>

For instance, let's explore how to add a new component onto Chelonia's aluminum extrusion.
1             |2
:-:|:-:
<img src="../Assembly_in_Fusion /Images/AddExis.jpg"  width= "100%"> Open the cloud -> right click -> Insert into current design.<br>Allign if needed. | <img src="../Assembly_in_Fusion /Images/NewExtrusion.jpg"  width= "100%">  With the extrude tool click on any Surface.<br>By selecting "Object" in Start parametr an arbitrary plane or surface might be chosen.
3           |4
<img src="../Assembly_in_Fusion /Images/1SoC.jpg"  width= "100%"> Assemble -> New component.<br> A new component should be visible in the construction tree. | <img src="../Assembly_in_Fusion /Images/1Sketch.jpg"  width= "100%"> After selecting ZY plane,the sketch to be extruded is finshed.



# Intermediate result
Now, let's make only the new component and its system of coordinates visible.
<img src="../Assembly_in_Fusion /Images/RightSoC.png"  width= "100%">
The outcome is that the SoC of the new component aligns with the global System of Coordinates of the entire assembly. However, this approach presents several drawbacks:

<ul>
  <li>It becomes less convenient to directly work with CAD/CAM/CAE tools on the individual part itself.</li>
  <li>The planes of symmetry of the component are affected.</li>
</ul>
Consequently, each time the file of this component is opened, numerous issues arise, such as aligning its SoC, which may not correlate with the geometry of the component, as it is defined by the SoC of the initial assembly.

# Tipps
Useful tipp 1             |Useful tipp 2
:-:|:-:
<img src="../Assembly_in_Fusion /Images/Visibility.jpg"  width= "100%"> Visibility of a body/sketch/origin/component/etc is controlled by the "eye" button | <img src="../Assembly_in_Fusion /Images/Transp.jpg"  width= "100%">  Clicking "Active" on the root element will turn off the transparency of other components.

# Right approach
Before creating any sketches, and after labeling a new component and pressing "OK," align the new SoC using the "Joint" tool.

<img src="../Assembly_in_Fusion /Images/RightSoC.jpg"  width= "100%"> The origin of the new component. The origin of the root element is also hidden.

<b>Tool <a href="https://www.youtube.com/watch?v=Bw08O6XsfDI&t=300s&ab_channel=NYCCNC">JOINT</a></b> (or similar videos on youtube)

RIGHT             |WRONG
:-:|:-:
<img src="../Assembly_in_Fusion /Images/WrongSoc.png"  width= "100%"> Origin alligns with geometry | <img src="../Assembly_in_Fusion /Images/RightSoC.png"  width="100%"  >Origin does not align with geometry
RIGHT             |WRONG
<img src="../Assembly_in_Fusion /Images/RightAS.png"  width= "100%"> 2 components - 2 different origins | <img src="../Assembly_in_Fusion /Images/WrongAS.png"  width="100%"  > Both origins at the same positioin.


What's the difference between new body and new component?
