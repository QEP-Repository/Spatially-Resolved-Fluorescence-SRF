# Spatially-Resolved-Fluorescence-SRF

This repository contains the data in the following paper: 

Puleio A., Rossi R.,  Grzesiak J., Walter A., Duschek F., and Gaudio P.  
*Spatially-Resolved Fluorescence (SFR) and Deep-Learning Algorithms for the measurements of agents' concentrations*  
Machine Learning: Science and Technology (accepted), 2025 

**ReadMe File for SRF Experimental Data**

The CSV file named SRFExperimentalData.CSV contains all the experimental data collected that make up the test dataset used.

Each line of the file corresponds to a spectrum acquired from the samples, and contains information about the sample and the position at which the spectrum was acquired.

The data in the file is divided as follows:

- The first column contains information on the type of case to which the sample belongs (e.g. Case A, Case B, etc.).

- The second column contains the tyrosine concentration value of the sample (in M)..

- The third column contains the tryptophan concentration value of the sample. (in M).

- The fourth column contains information on the spatial position where the fluorescence spectrum was acquired in the sample. (in cm).

- The fifth column to the last column contain the count values of the measured spectrum..

The separator used in CSV is “,”.

Every 4 lines of the file comprise the SRF map acquired from the sample used.




