# NG2-CSPG4
Input files for NG2/CSPG4 simulations

In the AA folder there are atomistic files for Gromacs:

prot_only.pdb = PDB structure of the full atomistic NG2/CSPG4
topol.top = contains the force field for the protein
dppc.itp = contains the force field for the DPPC molecule

In the CG folder there are Coarse-Grained files for Gromacs:
CG_Protein.pdb = Martini representation of the prot_only structure obtained using the Martinize 2 (command at the beginning of Protein_A.itp file)
Protein_A.itp = Martini Force Field for the CG_Protein.pdb
