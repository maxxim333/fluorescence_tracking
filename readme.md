The task starts from a database where each row is a cell, each column is a time point and each value is the fluorescence measurement. Cconsisted in the following:

Load time lapse fluorescence data from Matlab file "task1.mat" that is in the main course folder. Data are stored in two matrices: x_norm contains trajectories and t is a time vector

Plot (with labels) example cell tracetories | Tip: transpose the loaded data to get first dimension the same

Find peaks in each trajectories usin scipy library functions | Tip: Search for suitable functions in scipy manual

Calculate amplitude and period of oscillations | Tip: the period of oscillation is a distance between peaks in a single cell trajectory

Draw histograms of period distribution

Plot amplitude vs period with labels

Select ten cell trajectiories with the smallest periods and plot those as a heat map

Perform frequency analysis using FFT Fourier transformation and identify a dominant frequency in the signal
