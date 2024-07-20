# P-SNAPHU
Kun Jiang, Central South University, kunjiang@csu.edu.cn

This repo is used for unwrapping C-band coseismic interferograms of large earthquakes using the P-SNAPHU method

The demo is an example of the ascending interferogram for the 2016 Kumamoto earthquake


##### Notes ######

1. Install the SNAPHU unwrapping program before running
   The open source software SNAPHU could be obtained from https://web.stanford.edu/group/radar/softwareandlinks/sw/snaphu/

2. Prepare the data files and modify the paths based on your device in the P-SNAPHU_demo.m

3. Run it step by step in the P-SNAPHU_demo.m


%% Step 0: set path and read in parameters & files

%% Step 1: Range offset filtering
%  using Median filtering of homogeneous pixels (MFHP)

%% Step 2: Prior Gradient Refinement (PGR)

%% Step 3: Phase Unwrapping

###

If you find it helps, please cite the below reference:

Kun, J., Xu W., Xie L. (2024) Unwrap Intractable C-band Coseismic Interferograms: an Improved SNAPHU Method with Range Offset Gradients as Prior Information


