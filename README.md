# SARS-CoV-2-3D-Structures
Three-dimensional conformations of potential active compounds for SARS-Cov-2 treatment determined using quantum mechanics theories. The initial drugs investigated are based on the following work:

David E. Gordon et al, "A SARS-CoV-2-Human Protein-Protein Interaction Map Reveals Drug Targets and Potential Drug-Repurposing", bioRxiv, https://doi.org/10.1101/2020.03.22.002386

The accompanying manuscript: https://chemrxiv.org/ (TO-BE-DONE-SOON)

Geometry optimization performed using Psi4, with a convergence criterial of gau_tight, using the following theory levels:
1. HF/6-31G(d)
2. B97-D3BJ/cc-pVTZ (coming soon)

Frequency analysis have not yet be ran. From previous experience, most of the conformations are likely to be minima on the potential energy surface, but this is currently an assumption. Frequency will be eventually computed, and identified transition states will be removed.

The energies for each conformation are given on the comment line of each conformation. The conformations within each file are ranked from lowest to highest relative energy for the given theory level.

Investigated Drugs:
1. chloroquine - two isomers; 227 total HF/6-31G(d) conformations
2. valproic acid - 170 total HF/6-31G(d) conformations
3. silmitasertib - 30 total HF/6-31G(d) conformations
4. entacapone (coming soon)
