# XEUSS_WAXS_Data_Processing

Jupyter notebook workflow for loading Xeuss (GI)WAXS detector data (*.edf-Files).


1. Set paths and analysis parameters.
2. Load the detector frame and read the Xeuss header metadata.
3. Build a `.poni` calibration file from the detector header.
4. Transform the raw image to $(q_r, q_z)$ reciprocal space.
5. Apply the GIWAXS missing-wedge mask and save maps/arrays.
6. Optionally export rotational averages, chi cuts, indexed overlays, TIF copies, and simulation overlays.

To overlay indexed hkl on the data, GIWAXS data has to be simulated and indexed using e.g. INSIGHT https://doi.org/10.1107/S1600576723011159

