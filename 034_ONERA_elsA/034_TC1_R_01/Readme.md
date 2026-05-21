# High Lift Prediction Workshop 6 - Template Submission Files

This folder contains four files participants are expected to modify and submit for Test Case 1:

1. **FM.dat** = Converged or time-averaged Force and Moment data vs. angle of attack, multiple grid levels may be included
   - N.B.: append grid descriptor if providing results for multiple grids
3. **gridconvergence\_FM.dat** =  Converged or time-averaged Force and Moment data vs. grid level, multiple angles of attack may be included (this is a transpose of #1)
4. **nominalgrid\_cpcf.dat** = Surface pressure and skin friction distributions at locations corresponding to experimental pressure belts. These are defined [here](https://aiaa-hlpw.org/assets/HLPW6/tc1/TC1_Pressure_Rows.xlsx)
   - N.B.: remove nominal grid, add grid descriptor if providing results for multiple grids
6. **nominalgrid\_iterative.dat** = Solver iterative convergence with respect to iteration, or if time-dependent, with respect to convective time
   - N.B.: remove nominal grid, add grid descriptor if providing results for multiple grids

Additionally, participants should revise the Readme.md (this file) within their submission directory to include the following data:

# PARTICIPANT INFO:

# Name(s) and Organization(s):
Thomas RENAUD - ONERA

## Primary Email:  
thomas.renaud@onera.fr

## Primary Phone:  
+33 146734230

## Address:  
8 rue des Vertugadins 92190 Meudon FRANCE
 
# SOLVER INFORMATION:

## Solver Name and Version:
elsA (ONERA-SAFRAN Property)

## Basic Algorithm:  
cell-center FV solver, RANS equations

## Turbulence Model:  
Spalart-Allmaras

## Transition Method:
Insert details about transition model or method (if applicable)

## Convergence Criteria:
Insert convergence criteria here (if applicable)

## Miscellaneous:  
Insert any other information about the code/solver here

# Test Case 1 GRID & SOLUTION INFO (CRM-HLS)

## Name of committee-supplied grid used (if other, supply the info below):
Insert name of committee-supplied grid here


For non-committee grids...
## Grid-Generator Name and Version:  
Pointwise 2025.1.1

## Type (str, overset, unstr, etc):  
Unstructured Mixed elements (Hex,Prism,Voxel)

## Number of Total Nodes:  
20514263
28641173

## Number of Total Cells:
31377484
44145911

## Miscellaneous:  
both grids have the same boundary layer discretisation (first cell size, aspect ratio) Y+ ~0.3
surfacic refinement is applied between first and second grid (also with sources refinement)

# "TYPICAL" SOLUTION PERFORMANCE INFORMATION 
## Grid size:
44145911

## Computer Platform:  
Cascade Lake cores

## Number of Processors:  
288

## Operating System:  
Insert operating system here

## Compiler:  
Insert compiler here

## Run Time CPU:  
5.e-6 s/cell/ite

## Run Time Wall-Clock:  
Insert wall-clock time here

## Memory Requirements:  
Insert memory requirements here

## Convergence Details
Insert convergence information here (if applicable)

## Miscellaneous:
Insert miscellaneous information here regarding solution performance

# OTHER
Provide any other information desired here
