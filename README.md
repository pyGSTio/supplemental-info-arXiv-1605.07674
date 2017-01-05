[![DOI](https://zenodo.org/badge/78143804.svg)](https://zenodo.org/badge/latestdoi/78143804)
# Supplemental Information for the manuscript:
## "Demonstration of qubit operations below a rigorous fault tolerance threshold with gate set tomography"
(also [arXiv:1605.07674](https://arxiv.org/abs/1605.07674) with a slightly different title)

The purpose of this repository is to allow one to:

1.  Examine all experimental data presented in the paper.
2.  Reproduce the analysis performed on all data.
3.  Reproduce all plots.

Prior to running any notebooks, the reader should download and install the pyGSTi software,
available at [www.pygsti.info](www.pygsti.info).  [Version 0.9.2](https://github.com/pyGSTio/pyGSTi/releases/tag/v0.9.2) of the software was used when performing this analysis.

### Experimental Data:

All experimental data is included in the folder ExperimentalData.  Each file therein 
corresponds to a single experimental data run, taken on the date indicated in the file 
name, given in the format “yyyy_mm_dd”.  The remainder of the string is simply the 
historical file designation given at the time of data collection.

### Analysis notebooks:

All analyses for all results presented in the paper are included as IPython
notebooks in the `AnalysisNotebooks` folder.

### Computed Objects:

Running the analysis notebook `ExperimentalDataToResultsObjs.ipynb` will analyze all
experimental datasets and store the computed results objects in the folder `ComputedObjects`.
As this can take several hours to run, we have also included these precomputed results
objects in `ComputedObjects.zip`.

### Figures:

Figures that are generated in the IPython notebooks are stored here.
Note that all plots in the paper (save for Figures 3 and 4) are generated using the software 
DataGraph.  Here we only save figure reproductions using the freely available python 
package `matplotlib`.
