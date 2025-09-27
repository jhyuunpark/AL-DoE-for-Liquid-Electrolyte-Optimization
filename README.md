**[AL-DoE for Liquid Electrolyte Optimization]**
---
**SUMMARY**
---
AL-DoE code for nonflammable and durable liquid electrolyte optimization developed by CNU's Laboratory for Sustainable Process Engineering

**DESCRIPTION**
---
<img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/f226e947-4150-4c2f-94bb-363d24790ec0" />

This code was developed to optimize the composition of liquid electrolytes for lithium-ion batteries that ensure non-flammability while exhibiting excellent long-term cycle life. It implements Multi-objective Constrained Batch Bayesian Optimization (MCB-BO), an advanced framework that integrates multi-objective BO, constrained BO, and batch BO on top of a basic BO algorithm. Furthermore, by utilizing latter retention and final discharge capacity—metrics that allow long-term performance to be inferred from single-cycle data—the framework enables more efficient experimental optimization.
The proposed experimental compositions are sequentially validated, and the data are continuously updated to reflect the latest results. In this way, the system realizes an Active Learning-based Design of Experiments (AL-DoE) platform, which facilitates efficient and adaptive optimization of electrolyte formulations.

In this code, user can handle 3 input variables:
* PC content in solvent (vol.%)
* Type of Additive (X; VC; FEC)
* Concentration of Additive (wt.%)

and 4 output variables:
* SET (s/g)
* Retention (%)
* Latter retention (%)
* Final discharge capacity (mAh/g)

**ACKNOWLEDGEMENT**
---
This work was supported by Samsung Research Funding & Incubation Center of Samsung Electronics under Project Number SRFC-MA2202-04.
