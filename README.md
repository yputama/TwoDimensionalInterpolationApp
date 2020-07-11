# TwoDimensionalInterpolationApp
Matlab Apps for Two Dimensionals Interpolation functions from a scattered point cloud dataset (XYZ), i.e., Linear, Nearest neighbor, Natural neighbor, Cubic, and Spline interpolation.

Read and export data sets in ASCII cloud format (*.txt,*.asc,*.xyz,*.pts,*.csv).

Tuneable output grid interval in meter (in a uniform grid).

Option to make extrapolation.

Created with App Designer and Matlab 2019b libraries.

Version 1.0 notes:
- Read input point cloud (xyz) in ASCII cloud format (*.txt,*.asc,*.xyz,*.pts,*.csv)
- Option to add translation/scaling into original data to improve computational efficiency
- Plot original data
- Perform 2D interpolation (xyz) in a tuneable output grid interval (in meters)
- Selection to choose 2D interpolation methods, i.e., Linear, Nearest neighbor, Natural neighbor, Cubic, and Spline interpolation
- Option to make extrapolation
- Export output point cloud (xyz) in ASCII cloud format (*.txt,*.asc,*.xyz,*.pts,*.csv)