# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE

Step 1: Set Up Reference Axes & Base Grid

1. Draw primary vertical and horizontal centerline axes intersecting at the origin (0, 0).
2. Offset the main vertical centerline to the left and right by 50 mm to establish parallel centerlines at x = -50 and x = +50.
3. Offset the main horizontal centerline up and down by 60 mm to establish horizontal lines at y = +60 and y = -60.
4. Mark the 6 outer hole centers:
	• Top-left: (-50, 60)
	• Top-right: (50, 60)
	• Middle-left: (-70, 0) (offset 20 mm further left from x = -50)
	• Middle-right: (70, 0) (offset 20 mm further right from x = +50)
	• Bottom-left: (-50, -60)
	• Bottom-right: (50, -60)

<img width="547" height="307" alt="Screenshot 2026-10-12 105818" src="https://github.com/user-attachments/assets/e35c0589-4d6d-4997-8331-9f806ab97b12" />

Step 2: Draw Central Geometry

1. From center origin (0, 0): (Note: Specific sub-items under item 1 are cut off in the image, though the text in Step 4 indicates a central boundary of R40 and inner radii R21 and R32).
2. Construct the central web pattern:
	• Draw vertical parallel offset lines at x = ± 3 (total gap width 6 mm) through the center.
	• Construct 6 radial slots/spokes within the annular region between R21 and R32.

<img width="945" height="781" alt="image" src="https://github.com/user-attachments/assets/9504bca4-3e47-4b9c-a769-ed03027cefb6" />


Step 3: Construct Outer Circular Features

1. Hole Circles: Draw circles of radius R15 at all 6 outer center points.
2. Outer Bosses:
	• At top-left (-50, 60), top-right (50, 60), bottom-left (-50, -60), and bottom-right (50, -60), draw outer arcs of radius R21.
	• At middle-left (-70, 0) and middle-right (70, 0), draw outer concentric circles of radius R20.

<img width="945" height="673" alt="image" src="https://github.com/user-attachments/assets/e1762d45-8ec6-4d82-858f-52d9093199fd" />


Step 4: Connect Tangent Lines & Fillets

1. Outer Straight Tangents: Draw straight line segments tangent to the outer arcs connecting:
	• Top-left arc (R21) to middle-left arc (R20).
	• Bottom-left arc (R21) to middle-left arc (R20).
	• Top-right arc (R21) to middle-right arc (R20).
	• Bottom-right arc (R21) to middle-right arc (R20).
2. Top & Bottom Inner Fillets:
	• Create internal tangent fillets of radius R20 connecting the top-left arc (R21) and top-right arc (R21), resting smoothly against the central R40 boundary.
	• Create identical R20 internal fillets at the bottom connecting the bottom-left arc (R21) and bottom-right arc (R21).

<img width="687" height="770" alt="Screenshot 2026-11-26 085855" src="https://github.com/user-attachments/assets/ec09ba54-966f-4e2b-a266-719093750028" />


Step 5: Final Cleanup & Dimensioning

1. Trim all overlapping construction geometry to leave a clean outer boundary and inner features.
2. Apply centerlines, dimensions, hatch/shading, and radius annotations matching the technical drawing.

 
 ## SKETCH
 ![image](https://user-images.githubusercontent.com/113594316/198233336-dd9f5c19-481b-486a-928a-99c32a732f89.png)

 ## OUTPUT
 <img width="911" height="665" alt="Screenshot 2026-10-08 110603" src="https://github.com/user-attachments/assets/129780c2-2469-4a1e-864d-b05ef07527aa" />

 <img width="992" height="711" alt="Screenshot 2026-10-08 105605" src="https://github.com/user-attachments/assets/871a33f5-07b9-4c92-a17a-4384c5381301" />

 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
