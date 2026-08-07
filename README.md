# Drone_2

A README.md file that explains:

The objective of your project - Stef

**Project Objective**

The primary objective of this project is to design and evaluate two drone arm geometries to maximize payload capacity
while maintaining structural integrity. To accomplish this, MATLAB was used to perform thrust-to-weight calculations 
and finite element analysis (FEA) to evaluate the performance of each design under loading conditions. In addition to 
comparing the two geometries, the project includes a trade study of six materials commonly used in drone manufacturing.
Each material was evaluated based on factors such as weight, structural performance, and overall suitability to determine
the best material for the drone arm design. A budget analysis was also performed to compare the cost of each material 
and evaluate the trade-off between performance and affordability. By considering geometry, material properties, and cost, 
this project identifies a drone arm design that provides the best balance between payload capacity, strength, weight, and overall value.

  
__________________________________________________________________________________

**How to Run the Code and Models**

Choose one of the following options to run the MATLAB analyses:

**Option 1: Run Using MATLAB Desktop**

1: Download the Required Files

Download or clone the repository. Keep the following files in the same project folder:

- `drone1_final.mlx`
- `design2_final.mlx`
- `droneArmMaterials.mat`
- `taperedDroneArm.step`
- `drone_ellipse.step`

2: Open MATLAB

Open the MATLAB desktop application, such as MATLAB R2026a.

Set the MATLAB **Current Folder** to the folder containing the downloaded project files.

3: Run an Analysis

Open the Live Script for the design you want to analyze:

- Design 1: `drone1_final.mlx`
- Design 2: `design2_final.mlx`

Click **Run** to execute the entire Live Script.


**Option 2: Run Using MATLAB Online**

MATLAB Online allows you to open and run the project in a web browser without installing MATLAB on your computer.

A MathWorks account may be required.

### Design 1

[![Open Design 1 in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=tetsu235/Drone_2&file=drone1_final.mlx)

After the repository opens, select `drone1_final.mlx` and click **Run**.

### Design 2

[![Open Design 2 in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=tetsu235/Drone_2&file=design2_final.mlx)

After the repository opens, select `design2_final.mlx` and click **Run**.

__________________________________________________________________________________

Any required toolboxes or dependencies
Toolbox and dependency required:
* MATLAB Partial Differential Equation Toolbox
* droneArmMaterials.mat
* taperedDroneArm.step(external file, uploaded in the repository)
* drone_ellipse.step(external file, uploaded in the repository)
  
__________________________________________________________________________________
How to reproduce your results - Alex

  Software required: MATLAB R2026a
  
  Required Files:  
* MatLab live script
* droneArmMaterials.mat file
* taperDroneArm.step
* drone_ellipse.step

Make sure required files have been downloaded, once downloaded run the live script in MATLAB

## Expected Results for Design 1 (Tapered):

Max Payload Per Material (kg)
* Carbon Fiber Composite (CFRP) : 0.87
* Aluminum Alloy : 0.78
* Fiberglass Composite (GFRP) : 0.84
* PLA Plastic : 0.90
* ABS Plastic : 0.91
* Wood (Birch) : 0.95

FoS_Static
* Carbon Fiber Composite (CFRP) : 67.6545
* Aluminum Alloy : 31.7827
* Fiberglass Composite (GFRP) : 33.3252
* PLA Plastic : 7.1313
* ABS Plastic : 4.7080
* Wood (Birch) : 9.4160

XYZ Displacement (meters):
* Carbon Fiber Composite (CFRP)
  * X = 5.336e-10
  * Y = 2.044e-09
  * Z = 2.654e-08
* Aluminum Alloy
  * X = 5.528e-10
  * Y = 2.084e-09
  * Z = 2.693e-08
* Fiberglass Composite (GFRP)
  * X = 1.472e-09
  * Y = 5.701e-09
  * Z = 7.426e-08
* PLA Plastic
  * X = 1.111e-08
  * Y = 4.123e-08
  * Z = 5.306e-07
* ABS Plastic
  * X = 1.931e-08
  * Y = 7.208e-08
  * Z = 9.288e-07
* Wood (Birch)
  * X = 3.863e-09
  * Y = 1.442e-08
  * Z = 1.858e-07

## Final Results Design 1
 |Name|Weight Score|Static Score|Dynamic Score|Cost Score|Overall Score|
 |----|:--------:|:----:|:-:|:-:|:-:|
 |Carbon Fiber|0.8191|1|1|0.1923|0.7751|
 |Fiberglass|0.7648|1|0.6346|0.8065|0.7511|
 |Aluminum Alloy|0.6201|1|0.5171|1|0.6980|
 |Wood(Birch)|1|1|0.0614|1|0.6715|
 |ABS Plastic|0.9186|1|0.0143|1|0.6265|
 |PLA Plastic|0.8824|1|0.0319|1|0.6200|

## Expected Results for Design 2 (Ellipse):

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

## Final Results Design 2
 |Name|Weight Score|Static Score|Dynamic Score|Cost Score|Overall Score|
 |----|:--------:|:----:|:-:|:-:|:-:|
 |Fiberglass|0.7481|1|0.8707|0.7576|0.8181|
 |Carbon Fiber|0.8062|1|1|0.1786|0.7679|
 |Aluminum Alloy|0.5931|1|0.6545|1|0.7366|
 |Wood(Birch)|1|1|0.0764|1|0.6767|
 |ABS Plastic|0.9128|1|0.0178|1|0.6257|
 |PLA Plastic|0.8740|1|0.0388|1|0.6195|
