# SatDocking README


A small project made to perform best fit analysis and get the equation of an ellipse from pixel data formatted as 0 (sensor not detected) or 1 (sensor detected). The pixel data is of an image of a satellite with 7 sensors arranged in a circle (non-uniformly), while the satellite is rotating and has a certain unknown linear velocity. The program infers the equation of the ellipse of the circle viewed from a non-normal perspective, and computes the semi major, and semi-minor axes, which may be used to infer the rotational and translational velocities.


References:
1. https://datatofish.com/import-csv-file-python-using-pandas/
2. https://pythonexamples.org/pandas-dataframe-iterate-over-cells/
3. https://scipython.com/blog/direct-linear-least-squares-fitting-of-an-ellipse/
4. https://mmas.github.io/conics-matplotlib
