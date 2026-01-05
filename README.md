# CBCT Reconstruction – Curated Tools & Resources

A cleaned and structured collection of **CBCT (Cone-Beam CT) reconstruction–related** open-source tools, frameworks, and research projects.

---

## 🌀 General CBCT Reconstruction Frameworks

| Name                                                                                                 | Description                                                                                          |
| ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **[TIGRE](https://github.com/CERN/TIGRE)**                                                           | GPU-accelerated CBCT reconstruction toolbox (FDK, OS-SART, iterative methods). MATLAB & Python APIs. |
| **[ASTRA Toolbox](https://github.com/astra-toolbox/astra-toolbox)**                                  | Widely used tomography toolbox with CPU/GPU backends, Python & MATLAB interfaces.                    |
| **[CIL](https://github.com/TomographicImaging/CIL)**                                                 | High-level Python framework built on ASTRA/TIGRE; supports advanced optimization and regularization. |
| **[CCPi Regularisation Toolkit](https://github.com/TomographicImaging/CCPi-Regularisation-Toolkit)** | TV/TGV/NLL and other advanced regularizers; integrates with CIL.                                     |
| **[RTK](https://github.com/RTKConsortium/RTK)**                                                      | ITK-based C++/Python toolkit for CBCT reconstruction; industry- and research-grade.                  |
| **[LEAP](https://github.com/LLNL/LEAP)**                                                             | Livermore AI Projector for CT, supporting physics-aware and learning-based approaches.               |
| **[cbctrecon](https://github.com/agravgaard/cbctrecon)**                                             | Educational Python implementation of FDK and SART algorithms.                                        |
| **[PyTomography](https://github.com/PyTomography/PyTomography)**                                     | Lightweight Python framework for tomography research and teaching.                                   |

---

## 🛠️ Geometry Calibration & System Correction

| Name                                                                                                     | Description                                                              |
| -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **[CBCTCalibration](https://github.com/neutronimaging/CBCTCalibration)**                                 | Phantom-free CBCT geometric calibration tools (Python).                  |
| **[GeometricalSelf-Calibration](https://github.com/mamad-hosn/GeometricalSelf-Calibration)**             | Least-squares–based self-calibration with visualization.                 |
| **[CtCalib](https://github.com/matthiashar/CtCalib)**                                                    | Python-based cone-beam CT geometric calibration.                         |
| **[geometric_calibration](https://github.com/mrossi93/geometric_calibration)**                           | Template-fitting-based calibration for experimental CBCT systems.        |
| **[geometry_gradients_CT](https://github.com/mareikethies/geometry_gradients_CT)**                       | Studies reconstruction sensitivity to geometry perturbations.            |
| **[detector-calibration](https://github.com/physlin/detector-calibration)**                              | Detector gain/offset calibration, useful for low-dose imaging.           |
| **[offset-cone-beam-CT-reconstruction](https://github.com/Hallan99/offset-cone-beam-CT-reconstruction)** | Reconstruction with detector/orbit offsets and non-central trajectories. |

---

## 🎯 Advanced, Dynamic & Engineering-Focused Projects

| Name                                                           | Description                                                               |
| -------------------------------------------------------------- | ------------------------------------------------------------------------- |
| **[FORCASTER](https://github.com/ChristianToennes/FORCASTER)** | C++/CUDA framework for dynamic and time-dependent tomography.             |
| **[KCT_cbct](https://github.com/kulvait/KCT_cbct)**            | End-to-end CBCT system: acquisition, calibration, and reconstruction.     |
| **[CT-Recon](https://github.com/JueHo/CT-Recon)**              | Educational CT reconstruction algorithms and experiments.                 |
| **[helix2fan](https://github.com/faebstn96/helix2fan)**        | Helical-to-fan-beam rebinning utilities.                                  |
| **[mirt](https://github.com/JeffFessler/mirt)**                | Michigan Image Reconstruction Toolbox (classic iterative reconstruction). |

---

## 🤖 Deep Learning–Based Reconstruction & Artifact Reduction

| Name                                                                      | Description                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **[LION](https://github.com/CambridgeCIA/LION)**                          | Learning-based CBCT reconstruction and calibration (Cambridge CIA). |
| **[ArtifactReduction](https://github.com/CandleHouse/ArtifactReduction)** | Deep-learning framework for scatter and metal artifact reduction.   |
| **[PYRO-NN](https://github.com/csyben/PYRO-NN)**                          | Neural-network-based tomographic reconstruction methods.            |

---

## ☢️ X-ray Physics, Simulation & Scatter Modeling

| Name                                                           | Description                                                          |
| -------------------------------------------------------------- | -------------------------------------------------------------------- |
| **[XrayPhysics](https://github.com/kylechampley/XrayPhysics)** | X-ray spectra, attenuation, detector response models.                |
| **[VirtualCBCT](https://github.com/hagaakihiro/VirtualCBCT)**  | Virtual CBCT projection and reconstruction simulation environment.   |
| **[VirtualCT](https://github.com/hagaakihiro/VirtualCT)**      | CT system simulation for algorithm development and validation.       |
| **[openSSS](https://github.com/r-santo/openSSS)**              | Open-source single-scatter simulation tools.                         |
| **[MCNP](https://mcnp.lanl.gov)**                              | Monte Carlo N-Particle code for radiation transport (gold standard). |
| **[OpenMC](https://github.com/openmc-dev/openmc)**             | Modern open-source Monte Carlo particle transport simulation.        |

---

## 🖥️ Visualization & User Interfaces

| Name                                                               | Description                                        |
| ------------------------------------------------------------------ | -------------------------------------------------- |
| **[LEAPCT-UI-GUI](https://github.com/kylechampley/LEAPCT-UI-GUI)** | GUI frontend for LEAP CT reconstruction workflows. |

---

## 📚 Collections & Surveys

| Name                                                                                   | Description                                                        |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **[Awesome-CT-Reconstruction](https://github.com/LoraLinH/Awesome-CT-Reconstruction)** | Curated list of CT reconstruction papers, datasets, and codebases. |

---

### 🔍 Suggested Usage Guide

* **Algorithm research / GPU FDK & iterative methods**: TIGRE, ASTRA, RTK
* **Physics-aware or Monte Carlo scatter modeling**: OpenMC, MCNP, XrayPhysics
* **Geometry calibration & system debugging**: CtCalib, CBCTCalibration
* **Deep learning reconstruction / artifact reduction**: LION, PYRO-NN
* **Custom engineering systems**: KCT_cbct, FORCASTER


