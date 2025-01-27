This repository runs the Lorenz96 experiment described in "Featurizing Koopman Mode Decomposition For Robust Forecasting" by D. Aristoff, J. Copperman, N. Mankovich, and A. Davies. A description of the experiment can be found at https://arxiv.org/abs/2312.09146v3.

This repository also includes code, "FKMD.m", for running FKMD on any input and output data arrays, X and Y. In this setting, FKMD makes predictions starting from the last sample in the array X.

"lorenz96_sim.m" generates the data file lorenz96_data.mat.

"FKMD_lorenz96.m" runs FKMD on the Lorenz96 data. This generates a data file for each iteration.

"FKMD_analysis.m" analyzes these data files to create the plots that appear in the Lorenz experiment.
