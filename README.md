# 3COL-and-SAT-Exploration
Convert SAT instance into graph that is 3COL if the SAT CNF is satisfiable, and not 3COL if the SAT CNF is unsatisfiable. Verify colorings and variable assignments.

Usage:
Input SAT CNF to cnfto3col.py -> outputs a graph based on the standard SAT to 3COL reduction
Generate a coloring of this graph. (Can use 3col-exp.c to extract a coloring, or use independent algorithm)
Optional: use verify_3col.py to confirm coloring.
Input coloring into 3coltocnf.py -> outputs the variable assignments for your initial CNF corresponding to the coloring
Verify assignment in evaluate_cnf.py

Further exploration:
Use graphanalyzer.py to extract key features of the graph created for a given CNF (or an arbitrary graph).

File formats required:
Graphs in DIMACS format
SAT formulas in CNF format
Other file formats specified within script files
