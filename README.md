Stacking-Fault-Energy-Simulation-of-Al--Mn--Pd-Alloys-using-LAMMPS:
Performed LAMMPS simulations to compute stacking fault energies of Al–Mn–Pd alloys. Automated input generation using Python, used EAM potentials with minimization–NVT–NPT workflow, applied the DMLF model, and analyzed results using OVITO and Python.

Project Description:
- Developed an atomistic simulation workflow in "LAMMPS" to compute intrinsic, extrinsic, and twin stacking fault energies for Al–Mn–Pd alloys.
- Generated "189+ simulation input files" using automated Python scripts for FCC, HCP, and DHCP structures across multiple temperatures.
- Utilized "EAM potentials" and a multi-step pipeline (energy minimization → NVT heating → NPT equilibration) to obtain relaxed configurations.
- Applied the "Diffuse Multi-Layer Fault (DMLF)" model to compute normalized stacking fault energies and analyze temperature and compositional effects.
- Used "OVITO" for structural visualization and "Python (pandas, matplotlib)" for post-processing and plotting SFE trends.
- Compared pure, binary, and ternary alloy systems to evaluate the role of alloying elements on stacking fault energy stability.
