# Elevator CFD Simulation

This OpenFOAM project simulates the airflow around an elevator in motion, using dynamic mesh with prescribed velocity and structured mesh with blockMesh. The simulation is based on OpenFOAM version v2212.

[![Elevator CFD Simulation](https://img.youtube.com/vi/N00L1fOdbac/0.jpg)](https://youtu.be/N00L1fOdbac)


## Installation

To install and run the simulation, follow these steps:

* Clone this repository to your local machine using git clone https://github.com/leizhipeng/openfoam.git
* Navigate to the project folder: cd <project-folder>
* Compile the source files using wmake
* Run the simulation using ./Allrun

Note that you may need to modify the simulation parameters or input files to suit your specific needs. Please refer to the project documentation for more information.

## Simulation Steps

The simulation consists of the following steps:

* Create the geometry of the elevator and surrounding space using blockMesh.
* Generate the dynamic mesh using a prescribed velocity motion solver.
* Define the boundary conditions for the simulation, including inlet and outlet conditions and wall conditions for the elevator and surrounding space.
* Run the simulation using OpenFOAM's solver.
* Post-process the simulation results using ParaView or another visualization tool.

## Results

The simulation outputs the velocity and pressure fields for the airflow around the elevator. These results can be used to analyze the aerodynamic performance of the elevator design.

## Contact

If you have any questions or feedback about this OpenFOAM project, please feel free to contact me at zhipeng.lei@outlook.com .