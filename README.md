# Shockwave-Generator-using-Cavities
# Impact of Cavity Geometry on Shockwave Generation

This study investigates the impact of cavity geometry on shockwave generation and propagation in a supersonic flow. Shockwaves are compression waves that carry immense pressure, temperature, and momentum gradients, typically forming when a source imparts energy to a medium at a speed faster than the speed of sound. Various cavity shapes, including semicircular, elliptical, rectangular, triangular, and combinations thereof, are examined to understand their influence on peak pressure and amplification factors. Computational simulations are conducted using ANSYS Fluent 2023 R2. Results reveal that different cavity geometries lead to variations in peak pressure and amplification factors, with the semicircular cavity demonstrating the highest amplification. This research highlights the significance of cavity geometry in shockwave generation and suggests potential avenues for further investigation, including exploring additional parameters such as cavity dimensions and orientation using advanced computational and machine learning techniques.
## Geometry and Mesh

We used the Ansys Design Modeler to create the geometry of the shock tube with dimensions of 1000 mm x 60 mm. The dimensions of the cavities are as shown in Table 1. The mesh grid (discretization of geometry) is generated with Ansys Mesh. Edge sizing and Face meshing techniques are used to mesh the geometry.

##  Setup condition
The geometry divided into three parts driver section, driven
section and cavity section. 1D unsteady compressible flow
and Reynolds averaged Navier-Stokes (RANS) equations have
been solved using the commercial software ANSYS fluent
2023 R2. A density-based solver is used to solve the governing
differential equations (mass, momentum and energy) in a
coupled manner, and the ideal gas equation is used as the state
equation. The cell center values are extrapolated to the face
center using second order upwind scheme. The gradients at the
cell center are computed using the least square method. The
fluxes at the faces are calculated using the Roe-Flux difference
splitting method. Turbulence modelling has been done using
the inviscid model. The working medium is chosen to be air.
The boundary conditions for driver section pressure is 500,000
Pa and driven section pressure is 101,325 Pa.

## Post-processing:
We extracted the transient pressure data at 5 different points
in driven section which are at 300mm, 350mm, 400mm,
450mm, 499mm from the diaphgram for each cavity model.
As the test section is at the end of driven section we mainly
focused at the 499mm. The pressure contour of semi-circular
cavity shocktube is shown

![Shockwave Generation Semi Circular](https://github.com/chakradhar-23/Shockwave-Generator-using-Cavities/blob/faea02916725784c58cc7977f716e7d25e6970ba/shockwave%20generation%20semi%20circular%20one.png)





