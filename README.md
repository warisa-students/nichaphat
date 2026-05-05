# UIC860 Rail Deep Rolling 
This project explores High-Temperature Deep Rolling parameters on
Laser-Clad (Stellite 6) UIC860 Grade 900A Rail Steel
using DOE for micro-hardness prediction.
## Objective
- Preprocess experimental DOE dataset (3³ Full Factorial Design)
- Explore relationships between Deep Rolling parameters and HV response

## Dataset
- 54 samples (27 combinations × 2 replications)
- Base material : UIC860 Grade 900A Rail Steel
- Cladding : Stellite 6 (Co-based alloy powder)
- Factor A : Temperature [350 / 450 / 550 °C]
- Factor B : Rolling Pressure [180 / 200 / 220 bar]
- Factor C : Feed Speed [1400 / 1600 / 1800 mm/min]
- Response : Microhardness (HV) — Vickers Microhardness Test
## Tasks
- Data loading and inspection
- Feature scaling and normalization (Z-score, Min-Max, coded -1/0/+1)
- Main Effects Plot per factor
- Interaction Plots (A×B, A×C, B×C)
- Correlation analysis between factors and HV
- Linear Regression baseline (R², RMSE)
- ANOVA significance testing per factor
- Response Surface / Contour plot optimization