# Thermal-Fluid-Structure Coupling Simulation of Piston in Large Marine Diesel Engine

This repository hosts the project page for the paper: **"Thermal-fluid-structure coupling simulation of piston in large marine diesel engine"**, published in *Journal of Physics: Conference Series*, 2024.

## 📝 Abstract

Most traditional piston simulation approaches rely on **thermal-structure coupling**, where cooling boundary conditions are approximated using empirical formulas. This often leads to inaccuracies in temperature and stress prediction.

To address this challenge, we developed a **thermal-fluid-structure coupling simulation framework**. This method employs **Computational Fluid Dynamics (CFD)** to explicitly model the multiphase flow of cooling oil within the piston. By accurately identifying the cooling boundary conditions, we significantly enhance the fidelity of the subsequent structural analysis.

Results indicate that under maximum operating pressure, the piston's coupling stress peaks at **419.68 MPa**, which remains within the material's safety limits. The study identifies the junction of the piston head and the cooling chamber as the critical region for potential fatigue.

## 🚀 Key Features

- **Physics-Informed Boundaries:** Replaces empirical guesswork with rigorous multiphase CFD simulations to determine heat transfer coefficients.
- **Polyhedral Meshing:** Utilizes advanced meshing strategies for the irregular cooling cavity to balance accuracy and computational efficiency.
- **Safety Validation:** Provides a comprehensive verification of the piston's structural integrity under coupled thermal and mechanical loads.

## 📚 Citation

If you find this work useful for your research, please consider citing:

```bibtex
@article{luo2024thermal,
  title     = {Thermal-fluid-structure coupling simulation of piston in large marine diesel engine},
  author    = {Luo, Congcong and Zhao, Minghang and Zhang, Kai and Yu, Xiaoxia and Li, Junfu and Cui, Zhiquan},
  journal   = {Journal of Physics: Conference Series},
  volume    = {2827},
  pages     = {012020},
  year      = {2024},
  publisher = {IOP Publishing},
  doi       = {10.1088/1742-6596/2827/1/012020},
}
