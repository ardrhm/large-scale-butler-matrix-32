# large-scale-butler-matrix-32
Large-Scale Switched-Beam Butler Matrix Beamforming Network

This repository contains a research-grade MATLAB/Simulink implementation of a 32-by-32 Butler Matrix (BM) beamforming network (BFN) developed as a large-scale theoretical software demonstrator. The project models sequential excitation, phase-state generation, and array-factor reconstruction, enabling visualization of 32 distinct normalized beams and serving as a platform for BFN study and future extension.

Running instructions for the developed large-scale BM-BFN:
[1] Open “ButlerMatrixModel32x32.slx” in Simulink, but do not run it yet.
[2] In MATLAB, load the parameter file: load('StandaloneButlerMatrixParameters.mat');
[3] Run the Simulink model.
[4] After simulation, confirm that the phase data has been generated in the MATLAB workspace as “PhaseValuesDegToWorkspace32x32” and, optionally, in the saved file “PhaseValuesDegToFile32x32”.
[5] Run the array-factor (AF) script to plot the 32 normalized beams in a single Cartesian figure.
