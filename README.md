# π-Complex Formation: Norbornene + Pd(OAc)₂

## Computational Study
Systematic DFT investigation of π-complex formation between norbornene and Pd(OAc)₂ using **two functionals** and **two solvent models**.

### 📊 Calculation Matrix
| Functional | Gas Phase | Dichloromethane (SMD) |
|------------|-----------|------------------------|
| **PBE0**   | ✅ Done   | ✅ Done (endo/exo)     |
| **PBE**    | 🚧 In progress | 🚧 In progress     |

### 🧪 Details
- **Software**: ORCA 6.1.0
- **Basis set**: SARC-ZORA-TZVP (Pd), SARC-ZORA-TZVP (any elements)
- **Solvation model**: SMD for dichloromethane (ε = 8.93)
- **Key species**:
  - Reagents: Pd(OAc)₂, norbornene
  - π-Complexes: endo and exo isomers

### 🗂 Repository Structure
norbornene-PdOAc2-pi-complex/
├── functional_PBE0/ # PBE0 functional
│ ├── solvent_none/ # Gas phase calculations
│ │ ├── 01_reagents/ # Input structures
│ │ └── 02_pi_complex/ # Optimized complexes
│ └── solvent_DCM/ # Dichloromethane (SMD)
│ ├── 01_reagents/
│ └── 02_pi_complex/ # ✅ endo/exo complexes calculated
└── functional_PBE/ # PBE functional
├── solvent_gas/
└── solvent_DCM/

### 🔬 Current Status
- ✅ **PBE0/DCM**: reagents optimized, π-complexes (endo/exo) located
- 🚧 **PBE/DCM**: geometry preparation
- ⏳ **Gas phase calculations**: to be started after solvent studies

### 📌 Notes
- All **input files** (`.inp`, `.xyz`) are committed
- **Output files** (`.out`, `.gbw`) are ignored via `.gitignore`
- TS and IRC calculations pending for both functionals
