# SketchPID
P&ID Recognizer
This is the codebase of P&ID Sketch Recognition and Translation into Standardized Drawing.

Organization
Archive/ - Project related files and scripts that are no longer needed. Backed up for later use.
Project.ipynb - The main python backend for parsing sketch into P&ID graphs.
dotted.ipynb - Vision-based module for differentiating between continuous and dotted lines.
data.csv - Sample input file.
output.png - Sample output file.
RFC.sav - A compressed model for P&ID symbol classification. Use python pickle for extraction.
index.html - Frontend webpage. script.js - Frontend script for collecting user sketches.

Dependency
Python3
pandas
numpy
scikit-learn
schemdraw
How to run:
Go to the sketch interface and draw your P&ID graph.
Feed the output data.csv into the Python backend (Project.ipynb), which returns a digitized version of the P&ID drawing.
Footer
