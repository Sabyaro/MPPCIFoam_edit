# MPPCIFoam_edit: Modified MPPCIFoam Solver for Cylindrical Geometry

This repository contains a customized version of the `MPPCIFoam` solver from OpenFOAM, edited to simulate multiphase porous media flow within cylindrical geometries.

## 📌 Project Objective

The primary goal is to extend and adapt the original `MPPCIFoam` solver to accurately handle cylindrical coordinate systems—making it suitable for simulations such as:

- Multiphase flow in cylindrical porous channels
- Nuclear fuel rod cooling simulations
- Porous wick flow in heat pipes
- Radial flow in packed beds or porous shells

## 🔧 Key Features

- ✅ **Cylindrical Geometry Support**: Geometry and governing equations adjusted for radial and axial directions.
- ✅ **Porous Media Model**: Darcy and non-Darcy (Forchheimer) flow resistance terms included.
- ✅ **Multiphase Flow Capability**: Supports two-phase or multiphase transport in porous domains.
- ✅ **Custom Boundary Conditions**: Adapted for axisymmetric or radial inlet/outlet behavior.
