# OpenFOAM

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## **OpenFOAM Guide**
* [openFoamUserManual](https://github.com/yunoicytail/openFoamUserManual) - OpenFOAM


## **1. Solvers**
<details>
  <summary>Click to expand!</summary>
  
### _1.1 Aeroacoustics_
* Aeroacoustic Solver for weakly compressible flows. ([Hybrid-Methods-in-Openfoam](https://github.com/jiaqiwang969/Hybrid-Methods-in-Openfoam))
* Dynamic Library for Computational Aeroacoustics. ([libAcoustics](https://github.com/unicfdlab/libAcoustics))

### _1.2 Compressible Flow_
* Density based solver for steady and unsteady simulation of high speed compressible flows. ([rhoDST](https://github.com/DSTECHNO/rhoDST))

### _1.3 High-Order Methods_

#### _1.3.1 Discontinuous Galerkin Method_
* High Order Parallel Extensible CFD software. ([HopeFOAM](https://github.com/HopeFOAM/HopeFOAM)))

#### _1.3.2 Weighted Essentially Non-Oscillatory_
* WENO for FVM. ([WENOEXT](https://github.com/WENO-OF/WENOEXT))

### _1.4 Hybrid Solvers_
* Collection of hybrid Central solvers. ([hybridCentralSolvers ](https://github.com/unicfdlab/hybridCentralSolvers))

### _1.5 Immersed Boundary Method_
* Consistent closures for Euler-Lagrange models of bi-disperse gas-particle suspensions derived from particle-resolved direct numerical simulations. ([openHFDIB](https://github.com/fmuni/openHFDIB))

### _1.6 Multiphase_
* Volume of fluid solvers for turbulent isothermal multiphase flows. ([varRhoTurbVOF](https://github.com/wenyuan-fan/varRhoTurbVOF_2))
* blastFoam. ([blastFoam](https://github.com/synthetik-technologies/blastfoam)]
* A porous multiphase toolbox. ([porousMultiphaseFoam](https://github.com/phorgue/porousMultiphaseFoam))
* Lagrangian Particle Tracking on a GPU. ([GPULagrangianFoam](https://github.com/geekynils/GPULagrangianFoam)) - ([Thesis Link](https://github.com/geekynils/Thesis))
* Simulation of wave dynamics. ([olaFlow](https://github.com/phicau/olaFlow))

### _1.7 Molecular Dynamics_

#### _1.7.1 DSMC_
* hyStrath. ([hyStrath](https://github.com/vincentcasseau/hyStrath))

#### _1.7.2 DUGKS_
* Discrete unified gas kinetic scheme. ([dugksFoam](https://github.com/zhulianhua/dugksFoam))

### _1.8 Source Terms_
* Actuator line modeling of vertical-axis turbines. ([turbinesFoam](https://github.com/turbinesFoam/turbinesFoam))
* Generalization of Erik Svenning's solver. ([multipleDiskSimpleFoam](https://github.com/EdgarAMO/multipleDiskSimpleFoam))
* Actuator Cylinder. ([actuatorCylinderSimpleFoam](https://github.com/EdgarAMO/actuatorCylinderSimpleFoam-solver))

### _1.9 Others_
* several additional solvers for OpenFOAM. ([myFoam](https://github.com/furstj/myFoam))
* Dual-mesh hybrid LES/RANS solver. (hybridFoam](https://github.com/xiaoh/hybridFoam))

### _1.10 Libararies and Boundary Conditions_
* Partially reflecting and non-reflecting boundary conditions for simulation of compressible viscous flow. ([NSCBC-openfoam](https://github.com/jiaqiwang969/NSCBC-openfoam))
* LEMOS (University of Rostock) addons for OpenFOAM-2.4.x ([LEMOS-2.4.x](https://github.com/LEMOS-Rostock/LEMOS-2.4.x))
* A real-fluid based thermophysicalModels library OF-6. ([realFluidThermophysicalModels-6](https://github.com/danhnam11/realFluidThermophysicalModels-6))
</details>
  
## **2. Machine Learning in OpenFOAM**
<details>
  <summary>Click to expand!</summary>

* [smartsim-openFOAM](https://github.com/CrayLabs/smartsim-openFOAM)
* Flowtorch. ([flowtorch](https://github.com/FlowModelingControl/flowtorch))
* PythonFOAM: In-situ data analyses with OpenFOAM and Python. ([PythonFOAM](https://github.com/argonne-lcf/PythonFOAM))

</details>

## **3. Optimization**
<details>
  <summary>Click to expand!</summary>
  
* Optimal Shape Design in External. ([shapeOptimizationFoam](https://github.com/joslorgom/shapeOptimizationFoam))
* Discrete Adjoint with OpenFOAM. ([dafoam](https://github.com/mdolab/dafoam))
</details>

## **4. Post Processing**
<details>
  <summary>Click to expand!</summary>

### _4.1 Reduced-Order Modeling_
* [AccelerateCFD_CE](https://github.com/IllinoisRocstar/AccelerateCFD_CE) - AccelerateCFD
* [ITHACA-FV ](https://github.com/mathLab/ITHACA-FV) - POD-Galerkin reduced order methods for CFD using Finite Volume Discretisation: vortex shedding around a circular cylinder, 2017.
* [mlfoam](https://github.com/AndreWeiner/mlfoam) - OpenFOAM technical committee on data-driven modeling
</details>

## **5. Turbulence Modeling**
<details>
  <summary>Click to expand!</summary>
  
* ShihQuadraticKE turbulence model. ([OpenFOAM](https://github.com/sagarsaroha18/OpenFOAM))
* Several additional models. ([myTurbulenceModels](https://github.com/furstj/myTurbulenceModels))
</details>

# Tutorials:

## **Compressible Flow**
* shock boundary layer interactions in the transonic buffet flow of a compressor cascade. ([DLR-buffet](https://github.com/jiaqiwang969/DLR-buffet))


## **Turbulence Modeling**
* Parametric analysis for SSTtransition turbulence model. ([SSTtransition-turbulence-model](https://github.com/jiaqiwang969/SSTtransition-turbulence-model))
* Turbulence Model verification. ([Backward Facing Step](https://github.com/jiaqiwang969/backward-step))
* Turbulence Model verification. ([2D Bump](https://github.com/jiaqiwang969/Axis-2Dbump))



### snappyHexMesh
* [pipeflow_snappyHexMesh](https://github.com/theodoreOnzGit/pipeflow_snappyHexMesh) - OpenFoam pipeflow geometry generated using snappyHexMesh

### Dynamic Mesh
* [VAWTCleanCase](https://github.com/h7ris/VAWTCleanCase) - Vertical-Axis Wind Turbine.
* [VAWT-structured-mesh](https://github.com/EdgarAMO/VAWT-structured-mesh)
* [OpenFOAM-2D-VAWT](https://github.com/traviscarrigan/OpenFOAM-2D-VAWT)

### Programming
* [BasicOpenFOAMProgrammingTutorials](https://github.com/UnnamedMoose/BasicOpenFOAMProgrammingTutorials) - set of OpenFOAM® programming tutorials!
* [foam2Columns](https://github.com/ZhangYanTJU/foam2Columns) - foam2Columns

### Test Cases
* [cascade-shock_buffet Project](https://github.com/jiaqiwang969/DLR-buffet) - High‐Speed PIV of shock boundary layer interactions in the transonic buffet flow of a compressor cascade.
* [Flow-past-a-sphere-OpenFOAM](https://github.com/EdgarAMO/Flow-past-a-sphere-OpenFOAM)
* [Flow-past-a-car-OpenFOAM](https://github.com/EdgarAMO/Flow-past-a-car-OpenFOAM)
* [Von-Karman-Street-Cylinder](https://github.com/EdgarAMO/Von-Karman-Street-Cylinder)
* [airfoil2D](https://github.com/EdgarAMO/airfoil2D)
* [actuator-disk-farm](https://github.com/EdgarAMO/actuator-disk-farm)]
* [NTNU-HAWT-turbinesFoam](https://github.com/petebachant/NTNU-HAWT-turbinesFoam)
* [transonicAirfoilSolution](https://github.com/tahayasardemir/transonicAirfoilSolution)
* [transonicNozzle](https://github.com/tahayasardemir/transonicNozzle)
* [OpenFOAM-Cases-Interfluo](https://github.com/Interfluo/OpenFOAM-Cases-Interfluo) - OpenFOAM cases from my YouTube channel
* [NACAFoil-OpenFOAM](https://github.com/petebachant/NACAFoil-OpenFOAM) - OpenFOAM case files for simulating NACA foils.
* [openfoam_python](https://github.com/openfoamtutorials/openfoam_python) - Some Python utilities I found useful in manipulating OpenFOAM cases in automated simulation procedures.
* [airfoilFoam](https://github.com/socrates-ferna/airfoilFoam) - An OpenFOAM automated tool for airfoil 2D CFD analysis.
* [naca0012_shock_buffet](https://github.com/AndreWeiner/naca0012_shock_buffet) - OpenFOAM simulations of transonic shock buffets at a NACA-0012 airfoil.
* [Python script to run CFD analysis on airfoil using **OpenFOAM** to simulate and **gmsh** to generate mesh](https://github.com/enritoomey/airfoilFOAM)






