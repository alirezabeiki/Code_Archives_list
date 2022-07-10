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
* modification of rhoCentralFoam with RK4 schme. ([rhoCentralRKFoam](https://github.com/jiaqiwang969/rhoCentralRKFoam), [rhoCentralRK4Foam](https://github.com/SiboLi666/rhoCentralRK4Foam), [rhoCentralFoamRK4Sponge](https://github.com/jiaqiwang969/rhoCentralFoamRK4Sponge))
* Implict Coupled Simulations. ([ICSFoam](https://github.com/stefanoOliani/ICSFoam))
* Energy conserving numerical flux is coupled with AUSM+up dissipative fluxes. ([rhoEnergyFoam](https://github.com/davidem88/rhoEnergyFoam))

#### _1.2.1 All Mach Number_
* Semi-implicit hybrid solver based on Kurgranov-Tadmore scheme and PISO method. ([pisoCentralFoam](https://github.com/unicfdlab/pisoCentralFoam))

### _1.3 Combustion_
* A library for OpenFOAM to handel the PLOG keywords in reactions. ([PLOGArrheniusReactions](https://github.com/ZmengXu/PLOGArrheniusReactions))
* Transported JPDF Library and Solver for Reactive Flow Simulation. ([pdfFoam](https://github.com/wildmichael/pdfFoam))
* Using Cantera to calculate species reaction rates. ([CanteraChemistryModel](https://github.com/ZhangYanTJU/CanteraChemistryModel))
* This solver calls Cantera to update T psi mu alpha D in OpenFOAM. ([reactingCanteraFoam](https://github.com/ZhangYanTJU/reactingCanteraFoam))

### _1.4 High-Order Methods_

#### _1.4.1 Discontinuous Galerkin Method_
* High Order Parallel Extensible CFD software. ([HopeFOAM](https://github.com/HopeFOAM/HopeFOAM)))

#### _1.4.2 Weighted Essentially Non-Oscillatory_
* WENO for FVM. ([WENOEXT](https://github.com/WENO-OF/WENOEXT))

### _1.5 Hybrid Solvers_
* Collection of hybrid Central solvers. ([hybridCentralSolvers ](https://github.com/unicfdlab/hybridCentralSolvers))

### _1.6 Immersed Boundary Method_
* Consistent closures for Euler-Lagrange models of bi-disperse gas-particle suspensions derived from particle-resolved direct numerical simulations. ([openHFDIB](https://github.com/fmuni/openHFDIB))

### _1.7 Multiphase_
* Volume of fluid solvers for turbulent isothermal multiphase flows. ([varRhoTurbVOF](https://github.com/wenyuan-fan/varRhoTurbVOF_2))
* blastFoam. ([blastFoam](https://github.com/synthetik-technologies/blastfoam)]
* A porous multiphase toolbox. ([porousMultiphaseFoam](https://github.com/phorgue/porousMultiphaseFoam))
* Lagrangian Particle Tracking on a GPU. ([GPULagrangianFoam](https://github.com/geekynils/GPULagrangianFoam)) - ([Thesis Link](https://github.com/geekynils/Thesis))
* Simulation of wave dynamics. ([olaFlow](https://github.com/phicau/olaFlow))

### _1.8 Molecular Dynamics_

#### _1.8.1 DSMC_
* hyStrath. ([hyStrath](https://github.com/vincentcasseau/hyStrath))

#### _1.8.2 DUGKS_
* Discrete unified gas kinetic scheme. ([dugksFoam](https://github.com/zhulianhua/dugksFoam))

### _1.9 Source Terms_
* Actuator line modeling of vertical-axis turbines. ([turbinesFoam](https://github.com/turbinesFoam/turbinesFoam))
* Generalization of Erik Svenning's solver. ([multipleDiskSimpleFoam](https://github.com/EdgarAMO/multipleDiskSimpleFoam))
* Actuator Cylinder. ([actuatorCylinderSimpleFoam](https://github.com/EdgarAMO/actuatorCylinderSimpleFoam-solver))

### _1.10 Others_
* several additional solvers for OpenFOAM. ([myFoam](https://github.com/furstj/myFoam))
* Dual-mesh hybrid LES/RANS solver. (hybridFoam](https://github.com/xiaoh/hybridFoam))

### _1.11 Libararies and Boundary Conditions_
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
* Deploying deep learning in OpenFOAM with TensorFlow. ([TensorFlowFoam](https://github.com/argonne-lcf/TensorFlowFoam))

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

### _4.2 Others_
* OpenFoam postprocessing python tool. ([fluidfoam](https://github.com/fluiddyn/fluidfoam))
* Transform OpenFOAM fields to one single file by columns. ([foam2Columns](https://github.com/ZhangYanTJU/foam2Columns))


## **5. Turbulence Modeling**
<details>
  <summary>Click to expand!</summary>
  
* ShihQuadraticKE turbulence model. ([OpenFOAM](https://github.com/sagarsaroha18/OpenFOAM))
* Several additional models. ([myTurbulenceModels](https://github.com/furstj/myTurbulenceModels))
* Dynamic Smagorinsky. ([dynamicSmagorinsky](https://github.com/ZhangYanTJU/dynamicSmagorinsky))
* A library for wall-modelled Large-Eddy Simulation in OpenFOAM. Mirrored from. ([libWallModelledLES](https://github.com/timofeymukha/libWallModelledLES))
* A set of codes developed for LES in OpenFOAM. ([TurbLab](https://github.com/syavash20/TurbLab))
* Low-Reynolds rough wall functions for the kOmegaSST model from OpenFOAM. ([lowReRoughWallBCs](https://github.com/esteldunedain/lowReRoughWallBCs))
</details>

## **6. Utilities**
<details>
  <summary>Click to expand!</summary>
  
* Computational Fluid Dynamics (CFD) for FreeCAD based on OpenFOAM solver. ([CfdOF](https://github.com/jaheyns/CfdOF))
* How to choose the right schemes in openFOAM. ([fvSchemes](https://github.com/Veenxz/fvSchemes))
</details>

## **Tutorials**

### -0. A set of Good Tutorials**
* OpenFOAM Cases Generated by Veen. ([Veen_OpenFOAM_Cases](https://github.com/Veenxz/Veen_OpenFOAM_Cases))

### _1. Compressible Flow_
<details>
  <summary>Click to expand!</summary>
  
* shock boundary layer interactions in the transonic buffet flow of a compressor cascade. ([DLR-buffet](https://github.com/jiaqiwang969/DLR-buffet))
* Transonic Airoil. ([transonicAirfoilSolution](https://github.com/tahayasardemir/transonicAirfoilSolution))
* Transonic Nozzle. ([transonicNozzle](https://github.com/tahayasardemir/transonicNozzle))
* Transonic shock buffets at a NACA-0012 airfoil. ([naca0012_shock_buffet](https://github.com/AndreWeiner/naca0012_shock_buffet))
</details>

### _2. Dynamic Mesh_
<details>
  <summary>Click to expand!</summary>
  
* Vertical-Axis Wind Turbine. ([VAWTCleanCase](https://github.com/h7ris/VAWTCleanCase))
* Vertical-Axis Wind Turbine. ([VAWT-structured-mesh](https://github.com/EdgarAMO/VAWT-structured-mesh))
* Vertical-Axis Wind Turbine. ([OpenFOAM-2D-VAWT](https://github.com/traviscarrigan/OpenFOAM-2D-VAWT))
* Shape Optmisation of a Vertical Axis Wind Turbine using Invasive Weed Optimisation. ([Shape-Opt-VAWT](https://github.com/pranshupant/Shape-Opt-VAWT))
* This project implements a moving mesh technique on OpenFOAM to solve the case a weir gate opening. ([WeirWithMovingGate](https://github.com/esteldunedain/WeirWithMovingGate))
</details>

### _3. Incompressible Flow_
<details>
  <summary>Click to expand!</summary>
  
* Flow past an airfoil. ([airfoilFoam](https://github.com/socrates-ferna/airfoilFoam))
* NACA airfoil simulation. ([NACAFoil-OpenFOAM](https://github.com/petebachant/NACAFoil-OpenFOAM))
* Python script to run CFD analysis on airfoil using **OpenFOAM** to simulate and **gmsh** to generate mesh. ([Case](https://github.com/enritoomey/airfoilFOAM))
</details>

### _4. Mesh Generation_
<details>
  <summary>Click to expand!</summary>
  
#### _4.1 Block Mesh_
* Flow past a cylinder. ([Von-Karman-Street-Cylinder](https://github.com/EdgarAMO/Von-Karman-Street-Cylinder))
* Flow past an 2D Airfoil. ([airfoil2D](https://github.com/EdgarAMO/airfoil2D))

#### _4.2 snappyHexMesh_
* 3D Circular Pipe. ([pipeflow_snappyHexMesh](https://github.com/theodoreOnzGit/pipeflow_snappyHexMesh))
* Flow past a sphere. (Flow-past-a-sphere-OpenFOAM](https://github.com/EdgarAMO/Flow-past-a-sphere-OpenFOAM))
* Flow past a car. ([Flow-past-a-car-OpenFOAM](https://github.com/EdgarAMO/Flow-past-a-car-OpenFOAM))

#### _4.3 Adaptive Mesh
* This project shows how to use the gradient of flow variables as a criteria to control Adaptive Mesh Refinement (AMR) for OpenFOAM simulations. ([GradientAMR](https://github.com/esteldunedain/GradientAMR))
</details>


### _5. Optimization_
<details>
  <summary>Click to expand!</summary>
  
* Shape Optmisation of a Vertical Axis Wind Turbine using Invasive Weed Optimisation. ([Shape-Opt-VAWT](https://github.com/pranshupant/Shape-Opt-VAWT))
</details>
### _6. Source Terms_
<details>
  <summary>Click to expand!</summary>
  
* VAWT by ALM. ([NTNU-HAWT-turbinesFoam](https://github.com/petebachant/NTNU-HAWT-turbinesFoam))
* Wind farm by actuator disk. ([actuator-disk-farm](https://github.com/EdgarAMO/actuator-disk-farm)])
* This project implements a sink term applicable to the momentum conservation equation of the multiphase OpenFOAM solvers (interFoam, interIsoFoam), which attenuates velocities in the air phase. ([airVelocityAttenuation](https://github.com/esteldunedain/airVelocityAttenuation))
</details>

### _7. Turbulence Modeling_
<details>
  <summary>Click to expand!</summary>
  
* Parametric analysis for SSTtransition turbulence model. ([SSTtransition-turbulence-model](https://github.com/jiaqiwang969/SSTtransition-turbulence-model))
* Turbulence Model verification. ([Backward Facing Step](https://github.com/jiaqiwang969/backward-step))
* Turbulence Model verification. ([2D Bump](https://github.com/jiaqiwang969/Axis-2Dbump))
</details>

### _8. Utilities_
<details>
  <summary>Click to expand!</summary>
  
* Some Python utilities I found useful in manipulating OpenFOAM cases in automated simulation procedures.. ([openfoam_python](https://github.com/openfoamtutorials/openfoam_python))
* OpenFOAM cases from my YouTube channel. ([OpenFOAM-Cases-Interfluo](https://github.com/Interfluo/OpenFOAM-Cases-Interfluo))
</details>

## **Programming**
<details>
  <summary>Click to expand!</summary>
  
* [BasicOpenFOAMProgrammingTutorials](https://github.com/UnnamedMoose/BasicOpenFOAMProgrammingTutorials) - set of OpenFOAM® programming tutorials!
* [foam2Columns](https://github.com/ZhangYanTJU/foam2Columns) - foam2Columns
</details>






