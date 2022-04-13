# Data and Descriptors
This assignment, as the ones of the incoming weeks, is based on a data file that was generated in your instructor's research lab. The data file named protein_environ.csv contains more than 700 rows of data related to the atoms of a small protein (an insulin mutant, entry 1A7F in the Protein Data Bank). For each atom the file report the element label (first column), an atomic radius (R), some properties that are related to how close to the surface of the protein the atom is, as well as the cartesian coordinates (X,Y,Z, in the last three columns) of that atom, as obtained from crystallographic data.

Assignment 1: In the data_analysis.ipynb file, use basic statistics to analyze some of the atomic properties provided in the data file. Consider the data in the columns labeled SUR_CONT_5.0 (3rd column) and VOL_CONT_5.0 (9th column). For these two quantities compute the following: 
* Plot the histogram of the data
* Compute the mean value of these two properties for the atoms of the protein
* Compute the standard deviation of these two properties for the atoms of the protein

Assignment 2: In the mass_distribution.ipynb file, analyze the basic moments of the mass distribution of the protein.
* Create a new column of data with the atomic mass of each atom, assigned according to the element label and the average atomc mass of the element (e.g. H=1, C=12, O=16)
* Compute the zero-th moment of the mass distribution of the protein (a.k.a. the total mass)
* Compute the first moment of the mass distribution of the protein (a.k.a. the center of mass)
* Compute the second moment of the mass distribution of the protein (a.k.a. the moment of inertia) with respect to the center of mass
* For each atom of the protein compute a new property with its absolute distance from the center of mass.