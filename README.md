# PersistentHomology_CElegans
Code used for calculations in paper: "The growing topology of the C. elegans connectome"
all code in written in Julia, though calls through julia are made to R


Analysis_Main.ipynb contains *all* code ultimately used for the paper. Old scripts for null model calculations are included in the 'Null Models' folder, but these are re-created in Analysis_Main
- code assumes at times that it is being run on an 8-core processor. you may modify this to an n-core processor by changing the "addprocs(7)" in the first cell to "addprocs(n-1)"

- 'From Gene Expression File' holds all the raw data used, as well as data we cultivated through our analyses.

- 'Unused Considerations' contains some unused ideas that were tossed around in the analysis

