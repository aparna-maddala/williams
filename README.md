# RNA Folding Challenge

# environment management
conda activate rna-structure
- that's my dev environment where I download whatever packages I feel like. once I get something working I'll create a second environment with minimal dependencies etc.

# submission file
For each sequence in the test set, you can predict five structures. Your notebook should look for a file test_sequences.csv and output submission.csv. This file should contain x, y, z coordinates of the C1' atom in each residue across your predicted structures 1 to 5:

```
ID,resname,resid,x_1,y_1,z_1,... x_5,y_5,z_5
R1107_1,G,1,-7.561,9.392,9.361,... -7.301,9.023,8.932
R1107_2,G,1,-8.02,11.014,14.606,... -7.953,10.02,12.127
etc.
```

# TODO
- get a PyMOL license -- pending
- look at my bashrc
- set up kaggle account
- join competition
- select toy data files and document them properly
    - RNA pdb: https://www.kaggle.com/datasets/andrewfavor/uw-synthetic-rna-structures/data
    - get some ribosomal proteins too
- set up dash app: https://dash.plotly.com/minimal-app
- reach out to Petar about Ribovision functionality?

# scratchpad
- build one layer each for each level of structure
    - primary
    - secondary
    - tertiary - alpha helices, beta barrels
    - quaternary
- for ribosomal RNA as proof of concept, investigate how ribosomal proteins affect rRNA structure

# to read
- https://www.pnas.org/doi/10.1073/pnas.2112677119
- https://www.kaggle.com/competitions/stanford-ribonanza-rna-folding

# GUI/dash inspiration
- https://dash.gallery/dash-alignment-chart/
- ribovision and proteovision
- https://pymol.org/

# references
- https://www.kaggle.com/competitions/stanford-rna-3d-folding/overview
- https://www.nature.com/articles/s41467-021-23555-5