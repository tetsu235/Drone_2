# Drone_2

A README.md file that explains:

The objective of your project - Stef

  The primary objective of this project is to design and analyze two drone arm geometries with the goal of maximizing payload capacity.
  Using MATLAB, thrust-to-weight analysis and finite element analysis (FEA) were performed. A key component of the project is the selection 
  of an optimal material for the drone arms. Six materials commonly used in drone manufacturing, including carbon fiber composite and aluminum alloy,
  were evaluated through a trade study. The materials were compared based on factors such as structural performance, weight, and overall suitability 
  to determine the best material for the drone arm design.
  
__________________________________________________________________________________
How to run your code and models - Julian
  And Add interactive button


  Download the Required Files: 
  
    * MatLab live script
    * materials.m file
    * taperDroneArm.step
    * horizontal.step

  Run the MatLab code:
  
    1. Open MatLab
    2. Open the MatLab live script
    3. Click **run** to execute the analysis

  Ensure 'materials.m' is in the same folder as the live script so MatLab can access the materials properties.
  
__________________________________________________________________________________

Any required toolboxes or dependencies - Teppei
__________________________________________________________________________________
How to reproduce your results - Alex

  Software required: MATLAB R2026a
  
  Required Files:  
* MatLab live script
* droneArmMaterials.mat file
* taperDroneArm.step
* drone_ellipse.step

Make sure required files have been downloaded, once downloaded run the live script in MATLAB

Expected Results for Design 2 (Ellipse):

Max Payload Per Material (kg)
* Carbon Fiber Composite (CFRP) : 0.86
* Aluminum Alloy : 0.77
* Fiberglass Composite (GFRP) : 0.84
* PLA Plastic : 0.89
* ABS Plastic : 0.91
* Wood (Birch) : 0.95

FoS_Static
* Carbon Fiber Composite (CFRP) : 78.8070
* Aluminum Alloy : 36.1683
* Fiberglass Composite (GFRP) : 39.3702
* PLA Plastic : 7.9037
* ABS Plastic : 5.2661
* Wood (Birch) : 10.5323

XYZ Displacement (meters):
* Carbon Fiber Composite (CFRP)
  * X = 3.322e-09
  * Y = 3.787e-10
  * Z = 5.673e-08
* Aluminum Alloy
  * X = 3.364e-09
  * Y = 3.885e-10
  * Z = 5.752e-08
* Fiberglass Composite (GFRP)
  * X = 9.313e-09
  * Y = 1.052e-09
  * Z = 1.589e-07
* PLA Plastic
  * X = 6.618e-08
  * Y = 7.738e-09
  * Z = 1.133e-06
* ABS Plastic
  * X = 1.159e-07
  * Y = 1.350-08
  * Z = 1.983-06
* Wood (Birch)
  * X = 2.318e-08
  * Y = 2.699e-09
  * Z = 3.967e-07
