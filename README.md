# Dinesh Natarajan

**Aerospace engineer. I build engineering tasks, reference solutions and graders that test AI models on real design work.**

Bengaluru, India · MSc Aerospace Engineering, University of Salford · [LinkedIn](https://linkedin.com/in/dinesh-natarajan-baaa95206) · [dineshnatarajan02@gmail.com](mailto:dineshnatarajan02@gmail.com) · [CV (PDF)](./Dinesh_Natarajan_CV.pdf)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![OpenFOAM](https://img.shields.io/badge/OpenFOAM-CFD-1E5AA8)
![ANSYS](https://img.shields.io/badge/ANSYS-Mechanical-FFB71B)
![Abaqus](https://img.shields.io/badge/Abaqus-HyperMesh-5C2D91)
![CadQuery](https://img.shields.io/badge/CadQuery-OpenCascade-0A7E8C)
![MATLAB](https://img.shields.io/badge/MATLAB-Simulink-E16737)
![CATIA](https://img.shields.io/badge/CATIA_V5-Creo-005386)

## What I do

- **Engineering tasks for AI training and evaluation.** A task is a problem statement in the voice of a stress or manufacturing office, a disclosed engineering standard, a verified reference solution, and an automated grader that accepts any valid answer and rejects the textbook shortcut. I build all four, then calibrate difficulty against repeated agent runs and review the grader for ways a submission could score without doing the engineering.
- **Track record.** Six Hardware/CAD tasks accepted on Handshake AI's Project Insight, a Terminal-Bench 3 benchmark, in October 2026. Each ran in a separate verifier container with held-back cases and exact geometric grading. The last two were not solved in any of five trials by the benchmark's frontier model. Earlier, CFD and structural reinforcement-learning tasks at Alignerr (Labelbox), and aerospace solution review at Innodata.
- **The engineering underneath.** Finite-element analysis, CFD and aerodynamics, flight dynamics, fatigue and damage tolerance, B-rep geometry and GD&T.

## Selected work

| Project | What it is | Result | Stack |
|---|---|---|---|
| [ReconLoop](https://github.com/Dineshnae/reconloop) · [live demo](https://huggingface.co/spaces/dn2066/reconloop) | Settlement reconciliation agent graded against an answer key on held-out batches; a model breaks ties only where rules cannot | 83 tests, CI fails on a single wrong link across 20 held-out batches | Python, Gradio, Pyodide |
| [Engine bracket: FEA, topology optimisation, GD&T](https://github.com/Dineshnae/engine-bracket-fea-ansys) | Aircraft engine mount bracket in SAE 4130 from validated analysis to a toleranced, inspectable definition | 22 % lighter at a factor of safety of 1.73; worst-case ±0.35 mm and RSS ±0.206 mm stack-ups | ANSYS Mechanical, CATIA V5, ASME Y14.5-2018 |
| [Natural-laminar-flow airfoil study](https://github.com/Dineshnae/nlf-airfoil-cfd-xflr5) | NACA 63-215 and 64-210 against NACA 2412 across Re 500k to 3M, with 3D wing and stability derivatives | About 44 % higher L/D and 42 % lower drag at cruise | XFLR5, lifting line, vortex lattice |
| [Cessna 172 longitudinal flight dynamics](https://github.com/Dineshnae/aircraft-flight-dynamics-cessna172) | 4-state small-perturbation state-space model with eigenvalue analysis and four elevator inputs | Short-period ωn 5.60 rad/s, ζ 0.58, inside MIL-F-8785C; 6 of 6 V&V checks | MATLAB, Simulink |
| [Twin-boom surveillance UAV](https://github.com/Dineshnae/twin-boom-uav-design) | Conceptual design to a 3D-printed model in a three-person MSc team | 2.2 m span, 2.8 kg take-off weight against a sub-5 kg brief, 0.5 kg payload | SolidWorks, XFLR5 |
| [Aerodynamic surrogate](https://github.com/Dineshnae/nlf-airfoil-ml-surrogate) | Neural-network surrogate for airfoil Cl, Cd and L/D, benchmarked against three other regressors on a dataset calibrated to the XFLR5 study | 612 points, L/D R² 0.998, MAPE 2.9 % held out, 2.7 to 6.7 % on unseen Reynolds numbers, about 10⁶× faster than the solver | Python, scikit-learn |

## Experience

| When | Role |
|---|---|
| Sep to Oct 2026 | **Task author, Hardware/CAD**, Handshake AI, Project Insight. Six accepted terminal-based tasks with separate verifier images, held-back cases pinned by SHA-256, pytest graders, and a sandbox that runs the tool under test as an unprivileged user. |
| Sep 2026 to present | **Aerospace engineering expert, AI training**, Innodata (via Upwork). Review and rate aerospace question, solution and answer sets, with a written justification for every rating. |
| Jun to Sep 2026 | **Reinforcement-learning task author, engineering simulation**, Alignerr (Labelbox). Wing-planform and OpenFOAM tasks behind solver-health gates, OpenSeesPy retrofits, deterministic graders with hidden evaluation cases, difficulty calibrated against frontier-agent runs. |
| May 2023 to Sep 2025 | **Procurement and inventory operations supervisor**, Tops, Manchester. Led a 21-member operations team. |
| Oct 2020 to Apr 2021 | **Product design engineer (intern)**, Black Space Research and Development. Shell-element FE model of a rear underrun protection device in HyperMesh; three regulatory load cases with contact in Abaqus/Standard; governing case 234.6 MPa against 230 MPa yield. |

## Education and certifications

- **MSc Aerospace Engineering**, University of Salford, UK, 2023 (2:1). Dissertation: structural analysis of an aircraft engine bracket by the finite element method.
- **BTech Aerospace Engineering**, Karunya Institute of Technology and Sciences, India, 2021 (2:1).
- Master Diploma in Product Design, CADD Centre, 2022 ([certificate](./cadd_product_design_diploma.pdf)) · Airbus Supply Chain Specialist, Airbus Beyond, 2026 ([certificate](./Airbus_suplply_chain_specialist.pdf)) · Machine Learning Specialization, DeepLearning.AI and Stanford Online, 2026.

## Tools

Python (NumPy, SciPy, pandas, scikit-learn, pytest) · Bash and Linux · Docker · Git and GitHub Actions · ANSYS Mechanical · Abaqus/Standard · Altair HyperMesh · OpenFOAM · OpenSeesPy · XFLR5 (XFoil) · AeroSandbox · CadQuery and OCP (OpenCascade) · PTC Creo · CATIA V5 · MATLAB/Simulink

Open to contract and full-time work in engineering simulation, CAD and AI evaluation. Email is the fastest way to reach me.
