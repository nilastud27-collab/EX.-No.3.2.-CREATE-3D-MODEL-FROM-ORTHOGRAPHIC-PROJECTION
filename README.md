# EX No.3.2. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE: 02.11.2026
## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

## Step 1: Initial Setup 
1. Open Autodesk Fusion 360 and start a new design (File > 
New Design). 
2. Expand Document Settings in the Browser tree and verify 
that the active units are set to Millimeters (mm).

## Step 2: Create the Central Arched Body (Front View) 
1.Select Create Sketch and choose the XZ Plane (Front plane). 
2.Use the Line tool (L) to draw a horizontal baseline of 220 mm 
centered at the origin ( 110𝑚𝑚 on each side). 
3.Select Create > Arc > Center Point Arc, click the origin (0, 0) as the center, and draw a semicircle of radius 110 mm (R110) 
connecting the two ends of the baseline. 
4.Draw the inner rectangular slot at the bottom center: 
○ Draw two vertical lines of 60 mm upward at 60 mm to 
the left and right of the origin (total width 120 mm). 
○ Connect their top endpoints with a horizontal line of 120 mm and trim (T) the middle segment of the baseline to 
leave a single closed arch profile

<img width="437" height="371" alt="Screenshot 2026-11-19 235550" src="https://github.com/user-attachments/assets/948afa4d-4033-4380-b044-62ccab89a982" />

## Step 3:Extrude 
1.Click Finish Sketch. 
2.Select Extrude (E), click the closed arch profile, set Direction 
to Symmetric and Measurement to Whole Length, enter 150 mm, 
and click OK.

<img width="495" height="543" alt="Screenshot 2026-11-19 235556" src="https://github.com/user-attachments/assets/92390b6d-15df-47f5-86f1-18133d3509c1" />

## Step 4: Cut the Top Center Hole 
1. Select Construct > Offset Plane, choose the XY Plane, enter 110 mm upward (tangent to the top of the arch), and click OK. 
2. Select Create Sketch on this new construction plane. 
3. Draw a Circle (C) of diameter 20 mm (Ø20) centered at the origin (0, 0) and click Finish Sketch. 
4. Select Extrude (E), select the Ø20 circle, set Operation to Cut, set Extent Type to To Object, click the top inner ceiling 
face of the 60 mm slot, and click OK.

<img width="432" height="508" alt="Screenshot 2026-11-19 235603" src="https://github.com/user-attachments/assets/e0708e95-103c-4d3e-a842-d927c28adee1" />

## Step 5: Create the Base Lugs (Top View) 
1. Select Create Sketch and choose the XY Plane (Bottom plane). 
2. Draw two circles of diameter 120 mm (R60) centered at 150 
mm to the left and right of the origin (center-to-center distance 300 mm). 
3. Draw horizontal tangent lines connecting the top and bottom quadrants of both R60 circles into the central body to form two 
closed side lug profiles. 
4. Inside each R60 circle, draw a concentric hole circle of diameter 40 mm (Ø40).

<img width="487" height="313" alt="Screenshot 2026-11-19 235608" src="https://github.com/user-attachments/assets/64b20d79-2c7d-43cd-8612-3d49cb0c3bde" />

5. Click Finish Sketch. 
6. Select Extrude (E), select both side lug profiles (excluding the Ø40 inner circles), set Operation to Join, enter a height of 30 
mm upward, and click OK.

<img width="560" height="646" alt="Screenshot 2026-11-19 235618" src="https://github.com/user-attachments/assets/c245a968-1188-4695-9dbb-bdcd8ad4889d" />

## Step 6:Offset face

<img width="522" height="297" alt="Screenshot 2026-11-19 235624" src="https://github.com/user-attachments/assets/1c3faa5d-f34f-46a5-8ec2-5763755cc198" />

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198823540-38a1b79a-1f68-4876-add9-adf59b98b386.png)

## OUTPUT:
<img width="695" height="666" alt="Screenshot 2026-11-11 232926" src="https://github.com/user-attachments/assets/b3825459-1e5c-404e-96c8-128309bee664" />
<img width="950" height="666" alt="Screenshot 2026-11-11 231559" src="https://github.com/user-attachments/assets/15268ff8-9396-4f9c-85ca-f7b2ad883c2d" />

## RESULT:
Thus, 3D model is created from orthographic projection.

ILANILA VINNARASI.K.V
26017175
02.11.2026




