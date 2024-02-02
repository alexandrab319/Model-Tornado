# Model Tornado

## Introduction
This project focuses on the study of a constructed model representing the wind speed for a tornado. The analysis involves constructing a vector field to describe the flow of wind around the tornado's center. Calculations will be performed on the curl of the wind field, the work done on a lifted object, and the wind flow through reference surfaces. The project aims to discuss the behavior of the weather event predicted by the model.

## Necessary Coding Skills
- Creating/evaluating functions
- Plotting surfaces
- Plotting vectors
- Plotting curves

## The Project
### 1. Constructing the Model

### 1.1 Vector Field

  ##### a) Define the vector field representing wind direction:
  wdir(x, y, z) = ⟨-x - y, x - y, √2⟩
  ##### Is the vector field conservative? Find a unit vector field wdir and plot it.

  ##### b) Define the wind-speed function s(x, y, z) and the vector field w.  Plot the vector field w.
  s(x, y, z) = (2π - z) * √(x^2 + y^2)
  w = s(x, y, z) * wdir(x, y, z)

  ##### c) Plot the "event horizon" of the tornado (z = ln(x^2 + y^2)) and the vector field w for points on the event horizon.

### 1.2 Work Done on an Object
##### a) Simplify the model by relating force F(x, y, z) to air flow w. Determine the work done on an object along a given trajectory.

##### b) Plot the work done as a function of constants k and r0 for a specified trajectory.

##### c) Consider an alternative trajectory and calculate the work done. Compare qualitatively to the previous trajectory.

##### d) Plot the work done for the new trajectory as a function of constants k and r0. Compare qualitatively to the original trajectory.

### 1.3 Tendency to Pull and Lift Objects
##### a) Describe a right, circular cylinder's parametric equation, parallel to the z-axis, centered at the origin. Plot the surface and find its inward-pointing normal vector.

##### b) Find the inward flux of air across the cylinder as a function of its radius r0. Plot this function for a meaningful range of r0.

##### c) Define a surface bounded by the event horizon. Find its normal vector and describe the surface with inequalities.

##### d) Find the air flux upwards through the surface as a function of its height h. Plot this function and interpret its qualitative implications for the tornado.
