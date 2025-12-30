# π-Complex Formation: Norbornene + Pd(OAc)₂

Systematic DFT study of π-complex formation using **PBE0** and **PBE** functionals in **gas phase** and **dichloromethane (SMD)**.

## 📊 Status Overview

| Functional | Gas Phase       | Dichloromethane (SMD) |
|------------|-----------------|------------------------|
| **PBE0**   | ✅ Done         | ✅ Done (endo/exo)     |
| **PBE**    | 🚧 In progress  | 🚧 In progress         |

## 🧪 Methodology
- **Software**: ORCA 6.1.0  
- **Basis set**: SARC-ZORA-TZVP  
- **Solvation**: SMD (ε = 8.93 for DCM)  
- **Species**: Pd(OAc)₂, norbornene, π-complexes (endo/exo)

## 🗂 Repository Structure

- **`functional_PBE0/`** — расчёты с функционалом PBE0
  - `solvent_gas/` — газовая фаза
    - `01_reagents/` — исходные структуры
    - `02_pi_complex/` — π-комплексы
  - `solvent_DCM/` — дихлорметан (SMD)
    - `01_reagents/`
    - `02_pi_complex/` ✅ (эндо и экзо готовы)

- **`functional_PBE/`** — расчёты с функционалом PBE
  - `solvent_gas/`
  - `solvent_DCM/`

## 📌 Notes
- Все входные файлы (`.inp`, `.xyz`) сохранены.
- Выходные файлы (`.out`, `.gbw`) игнорируются (см. `.gitignore`).
- TS и IRC — в планах.
EOF# π-Complex Formation: Norbornene + Pd(OAc)₂

Systematic DFT study of π-complex formation using **PBE0** and **PBE** functionals in **gas phase** and **dichloromethane (SMD)**.

## 📊 Status Overview

| Functional | Gas Phase       | Dichloromethane (SMD) |
|------------|-----------------|------------------------|
| **PBE0**   | ✅ Done         | ✅ Done (endo/exo)     |
| **PBE**    | 🚧 In progress  | 🚧 In progress         |

## 🧪 Methodology
- **Software**: ORCA 6.1.0  
- **Basis set**: SARC-ZORA-TZVP  
- **Solvation**: SMD (ε = 8.93 for DCM)  
- **Species**: Pd(OAc)₂, norbornene, π-complexes (endo/exo)

## 🗂 Repository Structure

- **`functional_PBE0/`** — расчёты с функционалом PBE0
  - `solvent_gas/` — газовая фаза
    - `01_reagents/` — исходные структуры
    - `02_pi_complex/` — π-комплексы
  - `solvent_DCM/` — дихлорметан (SMD)
    - `01_reagents/`
    - `02_pi_complex/` ✅ (эндо и экзо готовы)

- **`functional_PBE/`** — расчёты с функционалом PBE
  - `solvent_gas/`
  - `solvent_DCM/`

## 📌 Notes
- Все входные файлы (`.inp`, `.xyz`) с- `02_pi_complex/` ✅ (эндо и экзо готовы)

- **`functional_PBE/`** — расчёты с функционалом PBE
  - `solvent_gas/`
  - `solvent_DCM/`

## 📌 Notes
- Все входные файлы (`.inp`, `.xyz`) сохранены.
- Выходные файлы (`.out`, `.gbw`) игнорируются (см. `.gitignore`).
- TS и IRC — в планах.
