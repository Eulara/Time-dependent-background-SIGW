# Scalar-Induced Gravitational Waves Probing Phase Transitions in the Standard Model and Beyond
Codes are in form of Jupyter Notebooks.

## Notebook1--SMbackground.ipynb
*To construction a adiabatic SM background from lattice QCD results.*

Input: lattice QCD table (list inside the notebook) and e-e+ period data (import from 'transferfunction/cs2.csv' and 'transferfunction/omega2.csv')

Output: cs,w background data -- 'cs2_new_merged.csv' and 'omega2_new_merged.csv' in C/T coordinate, 'T_cs2.csv' and 'T_w.csv' in T coordinate, and 'eta_cs2.csv' and 'eta_w.csv' in eta coordinate

## Notebook2--SIGW_EoS_QCD.ipynb
*To compute SIGW spectrum in the SM background*

Input: SM background 'cs2_new_merged.csv' and 'omega2_new_merged.csv' in C/T coordinate

Output: Phi, Green's function and kernel cache, GW spectrum results

## Notebook3--SIGW_EoS_model.ipynb
*To compute SIGW spectrum in the toy model background*

Input: 'cs2_model.csv' and 'w_model.csv'

Output: Phi, Green's function and kernel cache, GW spectrum results

## Notebook4--SIGW_EoS_BSM.ipynb
*To compute SIGW spectrum in the BSM background*

Input: SM background 'cs2_new_merged.csv' and 'omega2_new_merged.csv' and BSM model parameter (inside the notebook)

Output: Phi, Green's function and kernel cache, GW spectrum results
