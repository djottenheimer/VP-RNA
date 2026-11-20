# VP-RNA
Code related to the analysis of VP single nucleus RNA-sequencing. Accompanies the manuscript "Single-cell sequencing of rodent ventral pallidum reveals diverse neuronal subtypes with noncanonical interregional continuity" available at https://www.science.org/doi/abs/10.1126/sciadv.adp3059


The scripts in 'pre-processing' are specific for each experiment. They input the related gene expression matrices, perform any necessary quality control, identify neurons, and assign Allen Brain Cell Atlas labels using MapMyCells.

The scripts in this main folder use the pre-processed neurons from each experiment:

'VP-mouse-rat' analyzes neurons from our mouse and rat VP dissections.

'all-region-integration' compares neurons from VP, NAc, BNST, and POA experiments.

'high-fat-analysis' analyzes mouse VP cells from the different diet manipulations.

'custom-ABCA-integration' uses a clustering approach to assign ABC Atlas labels.
