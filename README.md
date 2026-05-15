# Aromatic Separation Unit — Benzene/Toluene Distillation Simulation

**NIT Warangal | Chemical Engineering | B.Tech 2nd Year**
**Gujjari Jayaprakash | 24CHB0A21 | 2025**

---

## Project Overview

This project simulates and optimizes a benzene-toluene distillation 
column modelling the **Aromatic Recovery Unit (ARU)** in a petroleum 
refinery — analogous to processes at IOCL Panipat, HPCL Vizag, 
BPCL Mumbai, and Reliance Jamnagar refineries.

---

## Key Results

| Parameter | Value |
|---|---|
| Optimal Reflux Ratio | R = 2.3 |
| Theoretical Stages | 12 |
| Distillate Purity | 95% Benzene |
| Bottoms Purity | 98% Toluene |
| Annual Steam Cost (optimal) | ₹448.57 lakhs/year |
| **Annual Savings vs R=4.0** | **₹231 lakhs/year** |
| **10-year savings** | **₹23.1 crores** |

---

## What This Project Covers

- **VLE Analysis** — Antoine equation + Raoult's Law → T-xy diagram
- **McCabe-Thiele Simulation** — Stage-by-stage composition profile
- **Sensitivity Analysis** — Reflux ratio vs stages vs energy
- **Operability Study** — Feed disturbance analysis (30%, 50%, 70% benzene)
- **Economic Analysis** — Steam cost optimization in ₹ lakhs/year

---

## Key Finding

At 30% benzene feed, fixed column settings give only **76.2% distillate 
purity** — demonstrating the need for DCS-based APC reflux control, 
as used in industrial refineries.

Operating at optimal R=2.3 instead of R=4.0 saves **₹231 lakhs/year** 
in steam costs — **₹23.1 crores over 10 years**.

---

## Tools and Methods

- **Language:** Python 3
- **Libraries:** NumPy, SciPy, Matplotlib, Pandas
- **Methods:** Antoine equation, Raoult's Law, McCabe-Thiele
- **Thermodynamic model:** NRTL (Non-Random Two Liquid)
- **Platform:** Google Colab

---

## Files in this Repository

| File | Description |
|---|---|
| `Aromatic_Separation_Unit_NIT_Warangal_2025.ipynb` | Complete Python simulation code |
| `Aromatic_Separation_Unit_Report_GujjariJayaprakash.pdf` | Full technical report |
| `Figure1_Txy_Diagram.png` | T-xy VLE diagram |
| `Figure2_McCabeThiele.png` | McCabe-Thiele stage diagram |
| `Figure3_Sensitivity_Reflux.png` | Sensitivity analysis graphs |
| `Figure4_Operability_Study.png` | Operability study results |
| `Figure5_Economic_Analysis.png` | Economic optimization graphs |

---

## Industrial Context

This simulation models the benzene-toluene separation column in an 
Aromatic Recovery Unit — a standard process in Indian petroleum 
refineries where reformate streams are processed to recover high-purity 
benzene and toluene for petrochemical applications.

---

## Resume Line

*Simulated benzene-toluene aromatic separation unit in Python 
(McCabe-Thiele, Antoine VLE, Raoult's Law); sensitivity analysis 
identifying optimal R=2.3; operability study under feed disturbances; 
economic analysis quantifying ₹231 lakhs/yr savings — modelled on 
petroleum refinery aromatic recovery process.*
